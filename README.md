This project demonstrates a complete end-to-end machine learning pipeline for predicting customer churn using the Telco Customer Churn dataset.

##  Objective

Predict whether a customer will churn (leave the service) using machine learning.


##  Features

- Data preprocessing using Scikit-learn Pipeline
- Handling missing values, scaling, and encoding
- Model training using:
  - Logistic Regression
  - Random Forest
- Hyperparameter tuning using GridSearchCV
- Model evaluation (Accuracy, Precision, Recall, F1-score)
- Exporting pipeline using Joblib
- Interactive Streamlit web application


## Tech Stack

- Python
- Pandas
- Scikit-learn
- Streamlit
- Joblib

##  Dataset

Telco Customer Churn Dataset

Features include:
- Customer demographics
- Services subscribed
- Billing information

Target:
- Churn (Yes / No)


##  How to Run

streamlit run app.py
