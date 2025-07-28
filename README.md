# Telco-customer-retention
Dataset for Telco customer churn prediction project

This repository contains a dataset related to **customer churn prediction** in the telecom industry. The aim is to analyze customer behavior and build models to **predict whether a customer will leave (churn)** or stay with the telecom service.

---

## 📂 Dataset Overview

The dataset includes **demographic info, account details, and services** used by each customer. It can be used to explore patterns, perform feature engineering, and build classification models.

- File Name: `telco_data.csv`
- Rows: ~7,000+
- Target Variable: `Churn`


## 🎯 Problem Statement

**To predict whether a customer will churn (leave the company), based on their service usage patterns, demographic information, and account behavior.**

Understanding why customers churn helps telecom companies improve customer retention strategies.



##  Features Description

| Column Name          | Description |
|----------------------|-------------|
| `gender`             | Male or Female |
| `SeniorCitizen`      | 1 if customer is a senior citizen, 0 otherwise |
| `Partner`            | Whether the customer has a partner |
| `Dependents`         | Whether the customer has dependents |
| `tenure`             | Number of months the customer has stayed |
| `PhoneService`       | Whether the customer has phone service |
| `MultipleLines`      | Whether the customer has multiple lines |
| `InternetService`    | Type of internet service |
| `OnlineSecurity`     | Whether online security is included |
| `OnlineBackup`       | Whether online backup is included |
| `DeviceProtection`   | Whether device protection is included |
| `TechSupport`        | Whether tech support is included |
| `StreamingTV`        | Whether streaming TV is included |
| `StreamingMovies`    | Whether streaming movies is included |
| `Contract`           | Type of contract (Month-to-month, One year, etc.) |
| `PaperlessBilling`   | Whether billing is paperless |
| `PaymentMethod`      | Customer's payment method |
| `MonthlyCharges`     | Monthly charges billed to the customer |
| `TotalCharges`       | Total charges billed |
| `Churn`              | Target: Yes or No |


## 💡Use Cases

- Churn prediction modeling
- Feature importance analysis
- Customer segmentation
- Retention strategy optimization


##  Tools Used

- Python
- Pandas, Matplotlib, Seaborn
- Scikit-learn / TensorFlow / Keras
- Google Colab
