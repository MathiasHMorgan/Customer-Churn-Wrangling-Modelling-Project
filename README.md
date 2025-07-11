![Python](https://img.shields.io/badge/Python-3.x-blue)
![PySpark](https://img.shields.io/badge/PySpark-Apache-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Model-green)

# 🔁 Customer Churn Prediction Project

Welcome to the **Customer Churn Wrangling & Modelling Pipeline**! This project demonstrates how to build a robust pipeline to ingest, clean, transform, and model customer churn data using scalable tools and techniques.

---

## 📖 Project Overview

This project focuses on a **telecommunications dataset**, where the goal is to identify customers likely to churn (cancel their services). It leverages industry-relevant tools like **PySpark**, **Pandas**, and **XGBoost**, integrating data engineering and data science practices into a unified workflow.

### 👨‍💼 Business Objective
To help the business **proactively retain high-risk customers** by predicting churn, enabling targeted marketing and retention strategies.

---

## ⭐ Key Features

### 🛠️ Data Engineering
- Ingestion and schema inspection with **Pandas**
- Data cleaning, transformation, and feature engineering
- Handling of missing values, categorical encoding, and outlier filtering

### 🤖 Machine Learning
- Feature selection and model training using **XGBoost** and ***PySpark***
- Evaluation via accuracy, precision, recall, and confusion matrix
- Hyperparameter tuning for improved performance

### 📊 Output
- Final churn predictions for each customer
- Insight into feature importance and churn-driving patterns

---

## 📂 Dataset

The data comes from a public telecom customer database, consisting of:
- Demographics (gender, age, tenure, etc.)
- Account info (contract type, payment method, charges)
- Service usage (internet, phone, tech support)
- Churn label (`Yes`/`No`)

---

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/MathiasHMorgan/Customer-Churn-Wrangling-Modelling-Project
cd Customer-Churn-Wrangling-Modelling-Projec
