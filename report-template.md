# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis is to predict how multiple factors affect whether a loan request is accepted or rejected.
* The data included the size and interest rate of the loans, the borrowers income, the borrowers debt-to-income ratio, the number of accounts the borrower has, the number of derogatory marks against the borrower, and the total debt of the borrower. What this model is attempting to predict is the loan status, whether it is accepted or rejected.
* The lending data included 77,536 rows of data on different loans.
* The first step was to clean the data and change categorical columns into boolean columns to enable the machine learning model to operate optimally. Next, we split the prediction target and features and then created training and testing sets of these data. We then defined the logistic regression model and fit the model to our training sets of data to begin the learning. Lastly, we tested the accuracy of the model's predictions and created a confusion matrix and classification report based off of the results.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    
    * Accuracy: 0.99
    
    * Precision: 0 = Healthy Loan, 1 = High-Risk Loan
        * 0: 1.00
        * 1: 0.86
    
    * Recall: 0 = Healthy Loan, 1 = High-Risk Loan
        * 0: 1.00
        * 1: 0.91
    
    
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* The logistic regression model worked very well with an accuracy of 99%. However, if you're not just trying to predict whether or not a loan will be accepted and instead looking to analyze why loans may be rejected then further training or another model may be better since the precision and recall of rejected loans was less accurate in this model.

