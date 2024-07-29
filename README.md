# Loan_approval

## Overview
This notebook demonstrates a machine learning workflow for predicting loan approval status using a dataset. The goal is to classify loan applications as either 'Approved' or 'Rejected' based on various features.

## Dataset
The dataset used is loan_approval_dataset.csv and includes the following columns:

loan_id: Unique identifier for each loan application
no_of_dependents: Number of dependents
education: Education level (Graduate/Not Graduate)
self_employed: Employment status (Yes/No)
income_annum: Annual income
loan_amount: Amount of loan
loan_term: Term of the loan in months
cibil_score: Credit score
residential_assets_value: Value of residential assets
commercial_assets_value: Value of commercial assets
luxury_assets_value: Value of luxury assets
bank_asset_value: Value of bank assets
loan_status: Loan approval status (Approved/Rejected)

Results
The Logistic Regression model achieved an accuracy score of approximately 90.5%. The confusion matrix provide further insights into the model’s performance, including true positives, true negatives, false positives, and false negatives.

Conclusion
The model demonstrates a high accuracy in predicting loan approval status. Further improvements could include tuning hyperparameters, trying different algorithms, or addressing class imbalance if necessary.
## Dependencies
pandas
matplotlib
seaborn
scikit-learn
