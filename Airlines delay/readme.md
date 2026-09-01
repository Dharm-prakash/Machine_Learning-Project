# ✈️ Airline Flight Delay Prediction using Machine Learning & Deep Learning

## 📌 Project Overview

This project focuses on predicting airline flight delays using historical flight data.

The project approaches flight delay prediction in two different ways:

1. **Regression** – Predict the exact arrival delay in minutes.
2. **Classification** – Predict whether a flight will be delayed by more than 15 minutes.

The project compares multiple Machine Learning and Deep Learning models to determine which approaches work best for flight delay prediction.

---

## 🎯 Objectives

- Analyze historical airline flight data.
- Perform data cleaning and preprocessing.
- Identify important factors associated with flight delays.
- Engineer useful temporal features.
- Predict the exact arrival delay using regression models.
- Predict delayed vs. non-delayed flights using classification models.
- Compare model performance using appropriate evaluation metrics.

---

## 📊 Dataset

The project uses a large historical airline flight dataset containing approximately **3 million flight records and 32 variables**.

The dataset contains information related to:

- Flight date
- Airline
- Departure delay
- Arrival delay
- Distance
- Air time
- Taxi-out time
- Taxi-in time
- Scheduled elapsed time
- Cancellation and diversion status
- Delay-related information

---

# 🔄 Project Workflow

```text
Raw Flight Data
       ↓
Data Loading
       ↓
Data Understanding
       ↓
Data Cleaning
       ↓
Feature Engineering
       ↓
Exploratory Data Analysis
       ↓
Feature Selection
       ↓
Encoding & Missing Value Handling
       ↓
Train-Test Split
       ↓
Feature Scaling
       ↓
      ┌───────────────────────┐
      │                       │
      ↓                       ↓
  REGRESSION             CLASSIFICATION
      ↓                       ↓
 ANN / LSTM / GRU / CNN   Logistic Regression
                          Gradient Boosting
                          KNN + SMOTE
      ↓                       ↓
 RMSE / MAE             Accuracy / F1 / ROC-AUC
      ↓                       ↓
 Model Comparison       Model Comparison
