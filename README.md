# Supervised Machine Learning

## Analysis Overview:
The goal is to prepare the data for a classification machine learning model, develop and evaluate a logistic regression model to predict applicants' loan statuses using historical lending data. This model aims to help the company make informed decisions on loan approvals or denials based on applicant characteristics.

## Results

Accuracy: the model achieved an accuracy of 99%, correctly predicting the loan status for 99% of the cases in the test set.

Precision and Recall: With a precision score of 1, the model predicts all non-defaulted loans perfectly, meaning all predicted non-defaults are actually non-defaults. This model correctly identified 99% of non-defaults in actual data with a recall score of 0.99. 


For defaulted loans (class 1), the precision score was 0.85, which means 85% of the loans were actually defaulted. With a recall score of 0.91, 91% of actual defaults have been identified correctly.


## Summary: 
Based on the evaluation metrics, I recommend using this logistic regression model to predict loan statuses. The model demonstrates high accuracy, correctly predicting 99% of loan outcomes. 
While the precision score for defaulted loans is 0.85, the recall score of 0.91 ensures the model effectively identifies most defaults. 
For non-defaulted loans, the model achieves perfect precision and nearly perfect recall, minimizing false positives. 
The model's strong performance across these metrics suggests it will be a robust and effective tool for making informed loan approval decisions, balancing precision and
recall to enhance operational efficiency.
