Date: "2023-01-19"  

Objective: Explain and predict Y=Class from X1 to X7 which includes variables like Area, Perimeter, and more using logistic regression; Y can be "Cammeo" or "Osmancik"  
We prepared our dataset by encoding "Cammeo" as 1 and "Osmancik" as 0 for logistic regression

Key actions: Detailed empirical analysis of the training data including variable transformations, examining histograms and box plots to identify distributions and correlations, 
such as Area and Convex Area showing similar distributions.

Using forward and both methods, we selected significant variables for the logistic regression model which included Major_Axis_Length, Convex_Area, Minor_Axis_Length, Area, Perimeter  
Implemented logistic regression and analyzed residuals to check model adequacy, identifying few outliers indicating a good model fit  

Prediction phase involved using our logistic regression model to predict the Class, assessing model accuracy with a confusion matrix on training data revealing an error rate of about 0.067,
indicating strong model performance  

ROC curves were generated to evaluate prediction quality in both training and test datasets, with AUC values around 0.98 suggesting excellent predictive power  

Conclusion: Metrics and methods validated our logistic regression model and the selection of variables used to build it, confirming the model's 
effectiveness in classifying rice types as Cammeo or Osmancik based on the specified features
