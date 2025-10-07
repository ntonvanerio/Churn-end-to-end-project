Telco Customer Churn Prediction: An End-to-End Machine Learning Project

A comprehensive data science project focused on building, tuning, and tracking a machine learning model to predict customer churn for a telecommunications company. The solution includes extensive data preparation, binary and one-hot encoding, feature scaling, and leverages XGBoost for classification. It features advanced Hyperparameter Optimization using Optuna and integrates MLflow for robust experiment tracking and model management, demonstrating an end-to-end MLOps workflow.



# 📉 Telco Customer Churn Prediction (End-to-End ML)

This repository contains an end-to-end machine learning project aimed at predicting customer churn for a telecommunications company. The goal is to identify customers who are likely to terminate their service, enabling proactive intervention by the business.

The project encompasses the full data science lifecycle, from Exploratory Data Analysis (EDA) and rigorous data preparation to advanced model training, hyperparameter optimization, and integration with MLOps tools.

## 🌟 Key Features

* **Data Preprocessing:** Handling missing values and encoding categorical features (binary columns mapped to 0/1, and multi-category columns using One-Hot Encoding).
* **Modeling:** Implementation of a powerful gradient boosting classifier (**XGBoost**) for high-accuracy prediction.
* **Hyperparameter Tuning:** Automated and optimized hyperparameter search using **Optuna** to maximize model performance.
* **MLOps Integration (MLflow):** Tracking experiments, parameters, metrics, and models using **MLflow** for reproducibility and centralized model management.

## 📊 Dataset

The project uses the publicly available **Telco Customer Churn dataset**  which contains information about:

* **Customer Demographics:** Gender, SeniorCitizen status, Partner, Dependents.
* **Account Information:** Tenure, Contract type, PaymentMethod, MonthlyCharges, TotalCharges.
* **Services:** PhoneService, MultipleLines, InternetService, and various internet add-on services (e.g., OnlineSecurity, TechSupport, StreamingTV).
* **Target Variable:** `Churn` (Yes/No).

## 🛠️ Technologies & Libraries

* **Python**
* **Pandas & NumPy:** Data manipulation.
* **Matplotlib & Seaborn:** Visualization (implied by imports in the notebook).
* **Scikit-learn:** Data transformation (`StandardScaler`).
* **XGBoost:** Core machine learning model.
* **Optuna:** Hyperparameter optimization framework.
* **MLflow:** Experiment tracking and Model Registry.
