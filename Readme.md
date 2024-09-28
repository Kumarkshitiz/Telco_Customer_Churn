# Customer Churn Prediction
1. Project Overview
This project aims to predict customer churn for a telecommunications company using machine learning techniques. By analyzing customer data, we build models that help identify customers likely to churn, enabling the company to take proactive measures to retain them.

2. Table of Contents
Project Overview
Dataset
Technologies Used
Model Selection
Evaluation Metrics
Results
Installation
Usage
Contributing
License
3. Dataset
The dataset used for this project is sourced from Kaggle. It contains customer information, including demographics, account information, and services used, which can impact churn.

 Key Features
customerID: Unique identifier for each customer
gender: Gender of the customer
SeniorCitizen: Whether the customer is a senior citizen
Partner: Whether the customer has a partner
Dependents: Whether the customer has dependents
tenure: Number of months the customer has been with the company
PhoneService: Whether the customer has a phone service
MultipleLines: Whether the customer has multiple lines
InternetService: Type of internet service
MonthlyCharges: Monthly charges of the customer
TotalCharges: Total charges of the customer
Churn: Target variable indicating if the customer has churned (Yes/No)

4. Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

5. Model Selection
Three models were evaluated for churn classification:

K-Nearest Neighbors (KNN): A simple, instance-based learning algorithm.
Logistic Regression: A linear model suitable for binary classification.
Neural Network: A more complex model mimicking human brain neurons.

6. Evaluation Metrics
The models were evaluated using the following metrics:

Accuracy
Precision
Recall
F1 Score
AUC-ROC curve

7. Results
After hyperparameter tuning, the best-performing model was Logistic Regression with the following results:

Best Parameters:
C: 100
Penalty: L2
Solver: Newton-CG
F1 Score: 0.609
Accuracy: 78.5%
The classification report and confusion matrix showed a higher performance in predicting non-churning customers compared to churned customers, indicating a potential class imbalance in the dataset.

