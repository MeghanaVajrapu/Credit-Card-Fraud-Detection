# Credit-Card-Fraud-Detection
Credit Card Fraud Detection using Machine Learning

This project aims to build a machine learning model to detect fraudulent credit card transactions.
The dataset used (creditcard.csv) contains 284,807 transactions made by European cardholders in September 2013, out of which 492 are fraudulent (0.172%). Since the dataset is highly imbalanced, the RandomOverSampler technique is applied to balance the classes.

📊 Project Workflow

1. Data Preprocessing

    Handling imbalanced data with RandomOverSampler

    Feature scaling with StandardScaler

2. Model Training

   Logistic Regression model trained with GridSearchCV for hyperparameter optimization

3. Evaluation

   Confusion Matrix

   Classification Report (Precision, Recall, F1-score)

   ROC Curve

   Visualization with Seaborn
