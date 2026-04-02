# 🫀 Heart Disease Prediction using Logistic Regression

The objective of this project is to analyze medical data and build a machine learning model capable of predicting whether a patient is at risk of heart disease based on various health indicators.

## 📋 Project Overview
Heart disease remains one of the leading causes of mortality worldwide. In this project, we utilized the **UCI Heart Disease Dataset** to understand the relationship between health metrics—such as age, cholesterol levels, and maximum heart rate—and the presence of heart disease.

### Key Objectives:
* **Data Cleaning & Preprocessing:** Handling raw data and ensuring model readiness.
* **Exploratory Data Analysis (EDA):** Understanding underlying trends and feature correlations.
* **Model Training:** Implementing a binary classification model using **Logistic Regression**.
* **Performance Evaluation:** Assessing accuracy using Confusion Matrix and ROC-AUC metrics.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 🐍
* **Libraries:**
    * `Pandas`: For data manipulation and analysis.
    * `Scikit-Learn`: For model training, scaling, and evaluation metrics.
    * `Matplotlib` & `Seaborn`: For data visualization and feature importance analysis.

---

## 📊 Methodology

### 1. Data Preprocessing
* **Label Encoding:** Converted categorical features like `Sex` into numerical format.
* **Feature Selection:** Selected critical health indicators: *Age, Sex, Resting BP, Cholesterol, Max HR, and Oldpeak*.
* **Standard Scaling:** Applied feature scaling to normalize data, improving model convergence and accuracy.

### 2. Model Training
We implemented **Logistic Regression**, as it is a highly effective and interpretable algorithm for binary classification tasks (Predicting Disease vs. No Disease).

### 3. Evaluation Metrics
The model achieved the following performance results:
* **Accuracy Score:** ~71.7%
* **ROC-AUC Score:** ~0.716

#### Confusion Matrix:
| | Predicted: No | Predicted: Yes |
| :--- | :---: | :---: |
| **Actual: No** | 71 | 31 |
| **Actual: Yes** | 27 | 76 |

---

## 📈 Feature Importance Analysis
The analysis highlights which factors most significantly influence the prediction:
* **Max Heart Rate:** Shows a **positive correlation** (higher heart rates are frequently associated with positive diagnoses in this dataset).
* **Oldpeak & Sex:** These features show a **negative impact/correlation** according to the model's coefficients.

---

## 👨‍💻 Author
**Hafiz Muhammad Yahya**
*Undergraduate Student (BS AI) at SMIU*
