# 🛍️ E-Commerce Customer Intelligence & Churn Prediction

## 📌 Project Overview

**E-Commerce Customer Intelligence & Churn Prediction** is an end-to-end Data Analytics and Machine Learning project developed to analyze customer purchasing behavior, identify meaningful customer segments, and predict customers who are at risk of churn.

The project transforms raw e-commerce transaction data into actionable customer insights using **Python, Exploratory Data Analysis (EDA), RFM Analysis, Customer Segmentation, Feature Engineering, and Machine Learning**.

The objective is to help businesses understand customer behavior, identify valuable and inactive customers, and support data-driven customer retention decisions.

---

## 🎯 Business Problem

E-commerce businesses collect large amounts of customer transaction data, but raw transaction records do not directly explain customer value or churn risk.

Businesses need answers to questions such as:

- Who are the most valuable customers?
- Which customers purchase frequently?
- Which customers have become inactive?
- Which customers are at risk of churn?
- Which customer segments require more attention?
- What behavioral patterns are associated with customer churn?

This project addresses these questions by converting transaction-level data into customer-level insights and applying machine learning for churn classification.

---

## 🚀 Key Objectives

- Clean and preprocess e-commerce transaction data.
- Perform Exploratory Data Analysis.
- Analyze customer purchasing behavior.
- Calculate Recency, Frequency, and Monetary (RFM) metrics.
- Segment customers based on purchasing behavior.
- Identify valuable, loyal, inactive, and at-risk customers.
- Engineer customer-level features for machine learning.
- Build and compare multiple churn prediction models.
- Evaluate model performance using appropriate metrics.
- Generate meaningful business insights from customer data.

---

## 📊 Dataset

The project uses an **Online Retail transactional dataset** containing historical e-commerce purchase information.

### Main Features

| Feature | Description |
|---|---|
| InvoiceNo | Unique transaction/invoice number |
| StockCode | Product identification code |
| Description | Product description |
| Quantity | Number of products purchased |
| InvoiceDate | Transaction date and time |
| UnitPrice | Price per product |
| CustomerID | Unique customer identifier |
| Country | Customer's country |

The transaction data is processed and transformed into customer-level analytical features for RFM analysis and churn prediction.

---

## 🏗️ Project Workflow

```text
Raw E-Commerce Data
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Customer-Level Feature Engineering
        │
        ▼
RFM Analysis
        │
        ▼
Customer Segmentation
        │
        ▼
Churn Feature Engineering
        │
        ▼
Machine Learning
        │
        ├── Logistic Regression
        ├── Random Forest
        └── XGBoost
        │
        ▼
Model Evaluation
        │
        ▼
Business Insights
