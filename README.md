# CCIS_CS6220
Data mining repo
### Assignment1 [87/100]
- Q2 "2/10 ["Highest ranked genre by Occupation" = Highest rank by mean value of rating for genres. And you need to use mean() instead of count() and "Genre" instead of "Title"]
-Q5 5/10[idxmax, idxmin - was performed on df instead of df_user - "df_user.iloc[df['rating'].idxmax()]"]

### Assignment2 [86/100]
1. 32/35 [Did not explain about the features and their types(-3)]
2. 32/35 [Did not explain about the features and their types(-3)]
3. 22/30 [3.2 Petal Length explains greatest amount of data(-5). 3.3 Apart from Lot Area, there are many features that have outliers (-3)]
### Assignment3 [93/100]
- Q1: [-5, for the question asking similarities or differences in the imputed values from mean and median, you should have taken this specific case and compared either the values directly or using boxplots]
- -2 [Sampling should be performed on the imputed data frame]

### Assignment4 [87/100]
1. 44/50 [(-3) "np.logical_and" will not give the correct fraction (Think about case where both actual and predict classes are 0).(-3) make_gaussian_quantiles is not the best model. Probably make-blobs is better than others]
2. 43/50 [(-2) "np.logical_and" will not give the correct fraction. (-3) Did not use single and complete linkage as given in question.(-2) You could have calculated fraction for each n_clusters combination here as well to understand how the accuracy got affected by the linkage type and n_clusters value.]
### Assignment4 [90/100]
- 1.1.1(-2, didn't mention final answer after range calculation)
- 2.4(-8, single plot that illustrates the value of PM column over time for each of the four cities, your plot doesn't give any visualizations and you haven't considered the timeline, X axis should be date/year)
- use markdown on your cells instead of comments
### Midterm [95/100]
1. 10/10
2. 10/10
3. 10/10
4. 10/10
5. 10/10
6. 10/10
7. 5/10 [(-2) Need more explanation on binary label distribution. (-3) Did not mention what is the expected TP/TN here]
8. 10/10
9. 10/10
10. 10/10 

### Quiz 1
- 2.5/10

### Quiz2 [6/10]
### Project proposal [95/10]

This is a good proposal guys. Your final portion of the document (where you discuss how this tool might be used) can benefit from more details, however. In particular, I think there is a lot more you can provide your users with. For instance, in addition to getting a prediction from your model telling them if their application will be approved or denied, you could also provide your users with a more detailed breakdown of what features contributed to that prediction the most. That way they can actually act upon that information and improve their application so as to increase their chances.

TOTAL 95/100

### Assignment6 - Services - [80/100]

### Presentation [95/100]

* Good presentation overall. This is an important problem for those who go through this process, and tools that can help people navigate through the complicated paperwork would certainly be welcomed.
* Below are a few notes that you can take into account when finalizing your report:
	- On your introduction, please clearly state what the actual problem you are trying to address is. Talk about who would use your tool and how it would benefit them. It was a bit hard to get these details from your presentation.
	- I'd like to see a lot more work from you guys in describing your dataset and providing your audience with some preliminary analysis / visualizations.
	- While it is fine to drop features that are not useful in training your model, it's also important to explain exactly why you dropped those and to show the work that went into making that decision. Make sure you are fully utilizing the data available to you, and if you do end up dropping some features, clearly state why.
	- Make sure you are encoding your nominal data properly. If any of your features are not numeric, first use get_dummies() to obtain a numeric representation of their values.
	- Adjust your service to actually return probability scores to your users. That way they get a bit more information about your predictions than just the outcome itself.
	- With this being a 3-person group, I'd also like to see a lot more work put into evaluating your model. Since your data is imbalanced, make sure to choose the correct metrics and methods to evaluate your classifier.

### Paper [95/100]

Well organized and formatted report! Thanks for following our layout suggestions closely!

Your introduction is great. The only minor comment I'd have here is that you could have included a bit more details around your final deliverable and how exactly that can be used by others.

Really great coverage of your data preprocessing, experiments, evaluation. And again, really nice formatting of your results and clear presentation. Nice use of Latex :)

Thanks for citing your references.

All in all this was a really great report and you did a good job incorporating our suggestions to it.

Perhaps a few more visualizations that highlight other aspects of your dataset would have been a bit more informative than the long list of missing value ratios (there it would have been sufficient to simply highlight the 5-10 columns with the most amount of missing data), but it's totally fine since you had it as an appendix

TOTAL 95/100
