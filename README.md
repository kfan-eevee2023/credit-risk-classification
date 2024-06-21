#20 Credit Risk Classification
Completed By: Kefan Liao


Overview
The goal of this project is to use various machine learning techniques to develop Logistic Regression Models and evaluate if it can more accurately predict healthy loans versus high-risk loans.  

The project follows these steps:
1. Data Preparation   -- The dataset is split into features and labels, further divided into training and testing sets.
2. Model Construction -- Logistic Regression Model with the Original Data: A logistic regression model is trained on the original training data (`X_train`, `y_train`).
                      -- Logistic Regression Model with Resampled Training Data: The original training data is resampled using the `RandomOverSampler` module to handle class imbalance. A logistic regression model is then trained on the resampled data.

File
credit_risk_classification.ipynb  -- Python code for the project

Results
Logistic Regression Model with the Original Data:
- Accuracy: 97.2%
- Precision (High-risk loans): 0.87
- Recall (High-risk loans): 0.95

Logistic Regression Model with Resampled Training Data:
- Accuracy: 99.6%
- Precision (High-risk loans): 0.87
- Recall (High-risk loans): 1.00

Summary  
The comparison shows that Logistic Regression Model with Resampled Training Data surpasses Logistic Regression Model with the Original Data in predicting high-risk loans and demonstrates higher overall accuracy. Logistic Regression Model with Resampled Training Data has a significant improvement in recall, correctly identifying all high-risk loans. So I recommend Logistic Regression Model with Resampled Training Data for identifying high-risk loans due to its enhanced performance and superior accuracy.
