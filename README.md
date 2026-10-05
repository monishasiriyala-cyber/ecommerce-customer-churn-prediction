# 🛍️ E-Commerce Customer Intelligence & Churn Prediction System

## 📌 Project Overview

The **E-Commerce Customer Intelligence & Churn Prediction System** is an end-to-end Data Analytics and Machine Learning project designed to understand customer purchasing behavior, segment customers based on their activity, and identify customers who are at risk of churn.

The project transforms raw e-commerce transaction data into meaningful customer-level insights using **data preprocessing, exploratory data analysis, RFM analysis, customer segmentation, feature engineering, and machine learning-based churn prediction**.

The primary goal is to help businesses understand **who their most valuable customers are, which customers are becoming inactive, and where customer retention efforts should be focused.**

---

## 🎯 Business Problem

E-commerce businesses generate large volumes of transaction data every day. However, raw transaction data alone does not clearly indicate:

- Which customers are highly valuable?
- Which customers purchase frequently?
- Which customers have become inactive?
- Which customers are at risk of leaving?
- Which customer segments require retention strategies?

Without proper customer analytics, businesses may lose valuable customers and spend marketing resources inefficiently.

This project addresses these challenges by converting transaction-level data into **customer-level behavioral insights** and applying machine learning to support churn identification.

---

## 🧠 Key Objectives

The major objectives of this project are:

- Clean and preprocess raw e-commerce transaction data.
- Perform exploratory data analysis to understand purchasing patterns.
- Analyze customer purchasing behavior.
- Calculate **RFM (Recency, Frequency, Monetary)** metrics.
- Segment customers based on their purchasing behavior.
- Identify high-value and at-risk customer groups.
- Build machine learning models for churn classification.
- Compare multiple classification algorithms.
- Evaluate model performance using classification metrics.
- Generate business-oriented customer insights.
- Support data-driven customer retention strategies.

---

## 📊 Dataset

The project uses an **Online Retail transaction dataset** containing historical e-commerce purchase records.

### Important Features

| Feature | Description |
|--------|-------------|
| InvoiceNo | Unique invoice/transaction number |
| StockCode | Product identification code |
| Description | Product description |
| Quantity | Number of units purchased |
| InvoiceDate | Date and time of transaction |
| UnitPrice | Price per product unit |
| CustomerID | Unique customer identifier |
| Country | Customer's country |

The raw transaction data is transformed into customer-level analytical data through preprocessing and feature engineering.

---

## 🏗️ Project Architecture

```text
                 ┌─────────────────────────┐
                 │     Raw Transaction     │
                 │          Data           │
                 └────────────┬────────────┘
                              │
                              ▼
                 ┌─────────────────────────┐
                 │   Data Cleaning &       │
                 │   Preprocessing         │
                 └────────────┬────────────┘
                              │
                              ▼
                 ┌─────────────────────────┐
                 │ Exploratory Data        │
                 │ Analysis (EDA)          │
                 └────────────┬────────────┘
                              │
                              ▼
                 ┌─────────────────────────┐
                 │ Customer-Level Feature  │
                 │ Engineering             │
                 └────────────┬────────────┘
                              │
                              ▼
                 ┌─────────────────────────┐
                 │      RFM Analysis       │
                 │ Recency | Frequency |   │
                 │ Monetary                │
                 └────────────┬────────────┘
                              │
                              ▼
                 ┌─────────────────────────┐
                 │ Customer Segmentation   │
                 └────────────┬────────────┘
                              │
                              ▼
                 ┌─────────────────────────┐
                 │ Churn Feature           │
                 │ Engineering             │
                 └────────────┬────────────┘
                              │
                              ▼
                 ┌─────────────────────────┐
                 │ Machine Learning Models │
                 │ LR | RF | XGBoost       │
                 └────────────┬────────────┘
                              │
                              ▼
                 ┌─────────────────────────┐
                 │ Model Evaluation &      │
                 │ Business Insights       │
                 └─────────────────────────┘
