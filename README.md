Customer Churn Prediction

This project aims to predict customer churn using machine learning. The dataset is from a Telco company and contains various features about customer demographics, usage, and account information. We build and deploy a machine learning model that predicts whether a customer will churn or not.

Project Overview

The project follows a standard machine learning pipeline:
- **Data Preprocessing**: Handle missing values, encode categorical variables, and scale numerical data.
- **Exploratory Data Analysis (EDA)**: Gain insights into the data through visualizations.
- **Model Training**: Train several classification models and select the best one based on performance metrics.
- **Model Evaluation**: Evaluate the model using accuracy, precision, recall, F1-score, and ROC-AUC.
- **Model Deployment**: Deploy the model using Flask to provide predictions via an API.

Dataset

The dataset used in this project is the Telco Customer Churn Dataset from [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn), which contains the following key features:
- CustomerID: Unique identifier for each customer.
- Gender: Whether the customer is male or female.
- SeniorCitizen: Whether the customer is a senior citizen or not (1, 0).
- Tenure: Number of months the customer has stayed with the company.
- MonthlyCharges: The monthly charges the customer incurs.
- TotalCharges: The total amount the customer has paid.
- Churn: Whether the customer churned (Yes, No).



