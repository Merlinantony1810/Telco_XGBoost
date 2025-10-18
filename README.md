# Telco Customer Churn Prediction using XGBoost

This repository contains a **customer churn prediction project** using the **IBM Telco Customer Churn dataset**.  
The goal is to predict which customers are likely to leave a telecom service, helping businesses improve retention strategies.

---

## Overview

The project uses **XGBoost**, a gradient boosting decision tree algorithm, because:

- It handles **non-linear relationships** between features effectively  
- Its ensemble of trees **reduces overfitting** compared to a single decision tree  
- Provides **feature importance and interpretability**  
- Works well on **tabular datasets** with categorical and numerical features  

---

## Dataset

The **IBM Telco Customer Churn dataset** contains customer information such as:

- Demographics: `gender`, `SeniorCitizen`, `Partner`, `Dependents`  
- Account details: `tenure`, `Contract`, `PaymentMethod`  
- Services: `PhoneService`, `InternetService`, `TechSupport`, `StreamingTV/Movies`, etc.  
- Charges: `MonthlyCharges`, `TotalCharges`  
- Target: `Churn` (Yes = 1, No = 0)  

Source: [IBM Watson Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
