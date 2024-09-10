SVD is typically ysed on sparse data, This includes data for a recommender system or a bag-of-words for text, If the data is dense , then is better to use the PCA method Neverthelese for simplicity , we will 
demonstrate for simplicity, we will demonstrate SVD on dense data in this section, at the fist step we use make_calisification() function and in the next setp we use Dimensionality reduction on this data set 
with fitting  a logistic regression  model, we will use a Pipeline where the first step performs the SVD transform and selects the 10 most important dimenssions or componants, and in the next step we find best
approach to evaluate the same transform and model with diffrent  numbers of input faetures and choose the number of features(amount of dimensionality reduction) that results in the best average performance and
in the final step we shall to choose to use SVD transform and logistic regression model combination as our final model,
