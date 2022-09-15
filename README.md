
# Challenge 12 Bootcamp

## Overview of the Analysis

* I utilised data to help predict wether a loan is clasified as Healthy (0) or High-Risk (1).
* The dependent variables are Loan Size, Interest Rate, Borrower Income, Debt to Income, Number of Accounts, Derogatory Marks, Total Debt
* The machine learning model deployed is logistic regresssion through sklearn to help with the same.
* Initially, the data was split into train and test sets.
* Then a model was created on these datasets. Furthermore, the training data was resampled through imblearn.over_samplings' RandomOverSampler and a new logistic regression model was created.


## Results

* Machine Learning Model 1:
  * The first model has an Accuracy score of 0.9918. , Precision scores of 1 and .85 for 0 and 1 respectively, and Recall scores of 0.99 and 0.91 for 0 and 1 respectively.

* Machine Learning Model 2:
  * The first model has an Accuracy score of 0.9936. , Precision scores of 1 and 0.84 for 0 and 1 respectively, and Recall scores of 0.99 and 0.99 for 0 and 1 respectively.


## Summary

* The second model seems to perform better for the problem we are trying to solve. 
* This is because, both models predict the 1 (High-Risk Loan) to roughly the same degree of accuraccy. However, Model 1 has a recall score of 0.91 for the 1 whereas Model 2 has a recall score of 0.99 for 1. Thus, Model 2 is better for the problem we are trying to solve.

