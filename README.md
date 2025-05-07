# 🛡️ E-Commerce Fraud Detection

This project was developed for IEOR 142A (Spring 2025) at UC Berkeley. Our goal is to build a machine learning model that detects fraudulent transactions on an e-commerce platform using behavioral and transactional features.

## 🚀 Project Overview

Fraudulent activity is a major challenge for online retailers, especially during high-traffic product drops. Our model aims to detect:
- Multiple orders to the same address with different user accounts
- Unusual purchase patterns (e.g., bulk orders at odd hours)
- Other behavioral red flags

## 📦 Dataset

We use a synthetic e-commerce dataset with the following features:
- Order ID, customer ID, timestamp
- Billing/shipping info
- Device/browser metadata
- Payment method
- Label: fraud vs. not fraud

> See: [`/data/merged_dataset.csv`](data/merged_dataset.csv)

## 🧠 Methods

We experiment with several classifiers:
- Logistic Regression (baseline)
- Random Forest
- XGBoost
- Isolation Forest (unsupervised baseline)

## 📈 Evaluation

Models are evaluated using:
- Precision, Recall, F1-score
- ROC-AUC
- Confusion Matrix

## 🛠️ Setup Instructions

Clone the repo and run:

```bash
pip install -r requirements.txt
