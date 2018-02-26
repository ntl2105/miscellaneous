# miscellaneous
The code in this notebook runs an OLS through all possible combinations of features of a dataset and selects the best model best on the following criteria: 

1. P-values of coefficients are all smaller than designated threshold #0.05 
2. Model residuals are normal (null hypothesis of normalcy of residuals are not rejected 
3. For models with more than 1 feature, all variance_inflation_factor(VIF) scores are less than 5. 

