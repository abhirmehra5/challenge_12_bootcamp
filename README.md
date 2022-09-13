
# Challenge 12 Bootcamp

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* I utilised data to help predict wether a loan is clasified as Healthy (0) or High-Risk (1).
* The dependent variables are Loan Size, Interest Rate, Borrower Income, Debt to Income, Number of Accounts, Derogatory Marks, Total Debt
* The machine learning model deployed is logistic regresssion through sklearn to help with the same.
* Initially, the data was split into train and test sets.
* Then a model was created on these datasets. Furthermore, the training data was resampled through imblearn.over_samplings' RandomOverSampler and a new logistic regression model was created.

## Results



* Machine Learning Model 1:
  * The first model has an Accuracy score of 0.9918. , Precision scores of 0.99 and .91 for 0 and 1 respectively, and Recall scores of 1 and 0.85 for 0 and 1 respectively.



* Machine Learning Model 2:
  * The first model has an Accuracy score of 0.9936. , Precision scores of 1 and 0.84 for 0 and 1 respectively, and Recall scores of 0.99 and 0.99 for 0 and 1 respectively.

## Summary


* The first model seems to perform better for the problem we are trying to solve. 
*  This is because, Model 1 predicts the 1s more acuurately than Model 2. It is more important to be accurate about High-Risk (1) loans than Healthy loans (0) to ensure the firm has a better risk profile.

