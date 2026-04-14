# 📊 Customer Lifetime Value (CLV) & Customer Segmentation Engine

This project is a machine learning system that analyzes customer behavior from multi-order e-commerce data to predict **Customer Lifetime Value (CLV)** and perform **customer segmentation**.

---

## 🎯 Project Objective

The goal of this project is to:
- Predict the future value of a customer (CLV)
- Segment customers into value-based groups (High / Medium / Low)
- Extract actionable business insights from purchase behavior

---

## 📁 Dataset

We use:

**ecommerce_customer_behavior_dataset_v2.csv**

Key characteristics:
- Multiple orders per customer (1–10 orders)
- Unique Order_ID per transaction
- Realistic simulated purchase behavior over time
- Includes:
  - Customer demographics
  - Order history
  - Product categories
  - Discounts and returns
  - Transaction totals

This version is designed for:
- RFM analysis
- CLV prediction
- Behavioral clustering

---

## 🧠 Problem Type

- Supervised Learning (Regression for CLV)
- Unsupervised Learning (Customer Segmentation)

---

## ⚙️ Pipeline Overview

1. Data Cleaning & Preprocessing  
2. Feature Engineering (RFM + behavioral features)  
3. CLV Target Construction  
4. Model Training (XGBoost / Random Forest)  
5. Customer Segmentation  
6. Evaluation & Insights  

---

## 📊 Key Features Used

- Recency (last purchase time)
- Frequency (number of orders)
- Monetary value (total spend)
- Discount usage ratio
- Return behavior
- Product category diversity

---

## 🤖 Model Output

The system outputs:
- Predicted Customer Lifetime Value (CLV)
- Customer Segment:
  - High Value
  - Medium Value
  - Low Value

---

## 🛠️ Tech Stack

- Python
- Pandas / NumPy
- Scikit-learn
- XGBoost
- Streamlit (for optional UI)

---

## 🚀 How to Run

```bash
pip install -r requirements.txt