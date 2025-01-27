# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to develop and evaluate a logistic regression machine learning model to predict credit risk. This model aims to assess the creditworthiness of borrowers on behalf of the lending company. The raw data includes loan size, interest rates, borrower income, debt-to-income ratio, etc. which aims to predict the loan_status variable, where 0 represents healthy loans and 1 represents high-risk loans. 

I split the data into training and testing sets before applying logistic regression to classify loans. Then, I evaluated the model using a confusion matrix and classification report to measure accuracy, precision, and recall scores. The aim was to achieve reliable predictions, particularly for high-risk loans, which is critical for minimizing financial losses.

## Results

Healthy Loans (0):
	•	Accuracy: 99%
	•	Precision: 1.00 (no false positives)
	•	Recall: 0.99 
	•	F1-Score: 1.00 (excellent precision and recall)

High-Risk Loans (1):
	•	Accuracy: 99%
	•	Precision: 0.86 (some false positives)
	•	Recall: 0.94 (detects majority of high-risk loans)
	•	F1-Score: 0.90 (strong overall performance)

## Summary

The logistic regression model is extremely effective with 99% accuracy in predicting loan status. For healthy loans the model performs perfectly with no false positives and a high recall. For high-risk loans it demonstrates strong recall (94%), fairly effectively identifying the majority of risky loans. Precision (86%) could be improved to reduce false positives.

I recommend using this model. It reliably identifies healthy loans and flags most high-risk loans. Continuing to optimize precision for high-risk loans could enhance its overall utility.
