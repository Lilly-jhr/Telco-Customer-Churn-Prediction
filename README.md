# Telco-Customer-Churn-Prediction: Logistic Regression vs. Neural Network

## Overview

This project analyzes the Telco Customer Churn dataset to predict customer churn using machine learning. It compares the performance of a traditional Logistic Regression model (implemented using Scikit-learn) against a simple Feedforward Neural Network (implemented using PyTorch). The analysis is performed within a Google Colab notebook.

## Business Problem

Customer churn is a major challenge for telecommunication companies, leading to revenue loss and increased acquisition costs. By accurately predicting which customers are likely to churn, the company can implement targeted retention strategies (e.g., special offers, improved support) to reduce churn and maintain profitability. This project aims to build and evaluate models suitable for this task.

## Dataset

The dataset used is the popular **Telco Customer Churn** dataset, commonly found on Kaggle.
*   **Source:** [Link to Kaggle Dataset (Optional but Recommended)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
*   **Content:** Contains information about ~7000 customers, including:
    *   Demographics (gender, senior citizen status, partner, dependents)
    *   Account information (tenure, contract type, payment method, paperless billing, charges)
    *   Subscribed services (phone, internet, online security, tech support, streaming, etc.)
    *   Target variable: `Churn` (Yes/No) indicating whether the customer left within the last month.

**Note:** The raw data file (`WA_Fn-UseC_-Telco-Customer-Churn.csv`) is **not included** in this repository due to its size. Please download it from the source link above.
