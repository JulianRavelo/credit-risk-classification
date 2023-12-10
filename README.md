# Credit risk classification - Challenge

## Overview of the Analysis

This repository contains historical data of a lending services company. Using this data, the credit_risk_classification.ipynb notebook has an analysis that intends to identify the creditworthiness of borrowers.  

The dataset has 77,537 rows of information, including loan size, interest rate, borrower income, total debt, and loan status, among others.  

Using the "loan status" column and a logistic regression model, we split the data into training and test datasets. Using the Sklearn library for Python, we could make predictions on the testing data and evaluate the model performance generating a confusion matrix and printing the classification report.  

## Results

As shown on precision values and f1-score, the logistic regression model has 100% accuracy in predicting a healthy loan and 88% in predicting high-risk loans. Even though 100% is a desirable value, the model is extremely well trained for this dataset on healthy loans and this might show a non-accurate behaviour for a different dataset. On the other hand, 88% is an adequate value for a high-risk loan model and might show a similar result on testing datasets.


## Summary

All in all, this logistic regression model would work appropriately in predicting a healthy or a high-risk loan. Although the precision and f1-score are higher when predicting healthy loans, changing the dataset might be a problem as the model is overtrained on this specific dataset. Regarding  high-risk loans, the model shows a value that suggests good results when changing the dataset. 

In my opinion, this model is recommended to be used by a lending services company to predict a healthy or a high-risk loan.
