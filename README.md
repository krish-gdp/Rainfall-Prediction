# Rainfall-Prediction

The goal of the project is to predict if its going to rain tomorrow or not based on the 24 different parameters.

In this the target data is initially unbalanced, so we balnced the data using Upsmapling.We imputed the categorical columns with mode, and then we have used the label encoder to convert them to numeric numbers. Once all the columns in the full data frame are converted to numeric columns, we imputed the missing values using the Multivariate Imputation by Chained Equations (MICE).

We trained the data using different models like logistic regression, decision trees,random forest classifier,XGBclassifier .
The performance of the each model is evaluated using accuracy_score, ROC curves,confusionmatrix etc.


