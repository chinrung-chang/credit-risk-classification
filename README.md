# credit-risk-classification
Module 20 Challenge
## Overview of the Analysis

This analysis is to evaluate the ML:logistic regression algorithm on our use case.
We want to know if it is a good model to predict the healthy or high risk loan based on the features below:

loan_size,interest_rate,borrower_income,debt_to_income,num_of_accounts,derogatory_marks,total_debt

## Results

* Logistic Regression model:
    * precision is 1 for predict healthy and 0.85 to predict high risk loan. Precision is defined as the ratio of true positives to the sum of true and false positives.
    * f1-score is 1 to predict healthy and 0.88 to predict high risk loan. The F1 is the weighted harmonic mean of precision and recall.
    * recall is 0.99 to predict healthy and 0.91 to predict high risk. Recall is defined as the ratio of true positives to the sum of true positives and false negatives.
    * support is 18765 cases for healthy and 619 cases for high risk

## Summary

* It is doing exceptional well to predict healthy loan and it is good to predict high risk loan on the model's performance.
* Based on the high risk loan will cause more damage. we are focusing on the prediction on high risk loan.
* If we can weigh on the total debt on the analysis, the company will know better if the model is good to use and to know the measure of the risk.
