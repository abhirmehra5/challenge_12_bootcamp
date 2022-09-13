# challenge_12_bootcamp

Overview of the Analysis
I utilised data to help predict wether a loan is clasified as Healthy (0) or High-Risk (1).
The dependent variables are Loan Size, Interest Rate, Borrower Income, Debt to Income, Number of Accounts, Derogatory Marks, Total Debt
The machine learning model deployed is logistic regresssion through sklearn to help with the same. 
Initially, the data was split into train and test sets.
Then a model was created on these datasets.
Furthermore, the training data was resampled through imblearn.over_samplings' RandomOverSampler and a new logistic regression model was created.

Results
Machine Learning Model 1:
The first model has an Accuracy score of 0.9918. , Precision scores of 0.99 and .91 for 0 and 1 respectively, and Recall scores of 1 and 0.85 for 0 and 1 respectively.
Machine Learning Model 2:
The first model has an Accuracy score of 0.9936. , Precision scores of 1 and 0.84 for 0 and 1 respectively, and Recall scores of 0.99 and 0.99 for 0 and 1 respectively.

Summary
The first model seems to perform better for the problem we are trying to solve. This is because, Model 1 predicts the 1s more acuurately than Model 2. It is more important to be accurate about High-Risk (1) loans than Healthy  loans (0) to ensure the firm has a better risk profile.


# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
