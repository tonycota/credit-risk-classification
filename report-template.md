# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. 

In this analysis we created a supervised machine learning model to predict was either a low risk (healthy class 0) or high risk (class 1). We were given a sizeable csv file to generate our data, factoring loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, total debt, and loan status. We implemented a logistic regression model from sklearn, split the data into training and testing sets, created a model that was fit with the training data, we also made predictions with the original test data. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.


* Precision
    * Low-Risk (Healthy) Loan (class 0): 100%
    * High-Risk Loan (class 1): 85%

* Recall
    * Low-Risk (Healthy) Loan (class 0): 99%
    * High-risk (class 1): 91%

* Accuracy: With an accuracy of 99%, we are confident our model classifies the instances correctly. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Due to the nature of having an imbalanced dataset for the high-risk loans compared to low-risk loans, there is room for improvement for our model to train from when it comes to high risk loans. There is less data for the model to learn from in regards to high-risk loans, if there was more, it could improve the over all precision and recall for our model. Yielding more conclusive results. 

It is far more important to prevent high-risk loans due to the reason the money being lent could ultimately be lost. 

With overall accuracy of 99% I would recommend this model. However, due to the simple fact that a lot of people who know they are not in good standing to receive a loan, generally don't attempt to receive a loan. Where as we see an opposite result for people who generally know they are in good standing to receive a loan. This could be the culprit of the imbalanced data that was generated. That would be the only thing I would recommend to change with the model; attempt to find proportionate data between high-risk and low-risk, however that may be easier said than done. 
