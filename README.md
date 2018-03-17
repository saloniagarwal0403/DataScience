#DataScience
Finding the most important features in a dataset and using the reduced model
Consider the crime data stored in crime.csv. We would like to understand how murder rate is related to the other variables in the dataset. Note that state is the “subject” here; it’s not a predictor, and region is a qualitative variable.
(a) Fit a multiple linear regression model to predict murder rate based on the other variables. Perform model diagnostics to check assumptions and perform any transformations needed to obtain a model that is reasonable with respect to the standard assumptions for linear models.
(b) Reduce your model by removing any unimportant variables (if such variables exist). Interpret the reduced model, including coefficients and r-squared. Perform a statistical test that compares the full model to the reduced model. Clearly state the hypotheses associated with this test and interpret the results.
(c) Use your final model to predict murder rate of a state whose predictor values are set at the average in the data for a quantitative predictor and the most frequent category for a qualitative predictor.
