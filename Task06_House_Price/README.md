# 🏠 House Price Prediction using XGBoost Regressor

This repository contains the implementation of a Machine Learning model designed to predict residential property prices. The project utilizes advanced regression techniques and feature engineering to estimate house values accurately.

## 📋 Project Overview
Predicting real estate prices is a fundamental task in data science. In this project (Task 6), we analyzed a housing dataset to identify primary price drivers and developed a high-performance regression model using **XGBoost**.

### Key Objectives:
* **Feature Preprocessing:** Scaling numerical variables like `SquareFeet` and `LotSize`.
* **Feature Engineering:** Creating a `Location_Score` through target encoding of Zip Codes.
* **Outlier Detection:** Identifying data anomalies using **Z-Score** analysis.
* **Model Training:** Leveraging the **XGBoost** algorithm.
* **Performance Evaluation:** Measuring model accuracy using **MAE**, **MSE**, and **RMSE**.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 🐍
* **Core Libraries:**
    * `Pandas` & `NumPy`: Data manipulation.
    * `XGBoost`: Gradient boosting regression.
    * `Scikit-Learn`: Scaling and metrics.
    * `Matplotlib`: Visualization.

---

## 📊 Methodology

### 1. Data Preprocessing & Scaling
* **Standardization:** `SquareFeet` and `LotSize` were normalized using `StandardScaler`.
* **Location Engineering:** Engineered a `Location_Score` based on the mean price per area.
* **Outlier Management:** Applied a Z-Score filter (threshold > 3).

### 2. Performance Metrics
* **MAE (Mean Absolute Error):** ~3,552.60
* **RMSE (Root Mean Squared Error):** ~4,917.11
* **$R^2$ Score:** **0.9996**
  
### 👨‍💻 Author
Hafiz Muhammad Yahya Undergraduate Student (BS AI) at SMIU
