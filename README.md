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
