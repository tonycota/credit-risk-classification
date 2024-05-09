# credit-risk-classification
Armando Cota's Submission for module 20


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

# Instructions for the Assignment

The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

NOTE
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

An overview of the analysis: Explain the purpose of this analysis.

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.