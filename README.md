# credit-risk-classification
The purpose of this analysis was to evaluate the risk associated with loans by predicting whether a given loan is healthy (low risk) or high risk of default. By leveraging machine learning techniques, the objective was to create a predictive model that can assist financial institutions in making informed lending decisions.

The dataset contained historical financial information about loan applicants, including factors such as income, debt-to-income ratio, loan amount, and other credit-related metrics. The target variable was the loan_status column, where:

0: Healthy loan (low risk)
1: High-risk loan (likely to default)
Stages of the Machine Learning Process:
Data Preparation: Loaded the lending_data.csv dataset, inspected for missing values, and defined the features (X) and target variable (y).
Data Splitting: Split the data into training (75%) and testing (25%) sets using train_test_split with a random_state of 1.
Model Selection: Applied the LogisticRegression algorithm, a commonly used classification method for binary outcomes.
Model Training: Trained the logistic regression model on the training data (X_train and y_train).
Model Evaluation: Used the confusion matrix and classification report to assess the model's performance.
Results
Machine Learning Model: Logistic Regression
The logistic regression model demonstrated strong performance with high accuracy and balanced metrics across both healthy and high-risk loans.

Overall Accuracy: 99%
Performance for Healthy Loans (0):
Precision: 1.00 – All predicted healthy loans were truly healthy.
Recall: 0.99 – 99% of actual healthy loans were correctly identified.
F1-Score: 1.00 – Reflects excellent balance between precision and recall.
Performance for High-Risk Loans (1):
Precision: 0.86 – 86% of loans predicted as high-risk were truly high-risk.
Recall: 0.94 – 94% of actual high-risk loans were correctly identified.
F1-Score: 0.90 – Strong balance between identifying true positives and minimizing false positives.
Summary and Recommendation
Based on the results, the logistic regression model is highly effective in predicting credit risk, achieving a 99% accuracy and strong recall for high-risk loans (94%). This is crucial in financial decision-making, as identifying high-risk loans helps mitigate potential losses.

Recommendation:

Use the Logistic Regression model: It provides reliable predictions while maintaining a low false-negative rate, ensuring most high-risk loans are correctly flagged.
Focus on Recall for High-Risk Loans: Since predicting high-risk loans accurately is more important than avoiding false positives, the model’s high recall (94%) makes it suitable for deployment.
In conclusion, this model can be confidently recommended for use in credit risk assessment, ensuring that lending institutions can make more informed and secure loan approval decisions.