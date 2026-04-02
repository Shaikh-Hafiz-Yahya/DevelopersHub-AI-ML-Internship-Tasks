🫀 Heart Disease Prediction using Logistic Regression
The objective of this project is to analyze medical data and build a machine learning model capable of predicting whether a patient is at risk of heart disease based on various health indicators.

📋 Project Overview
Heart disease remains one of the leading causes of mortality worldwide. In this project, we utilized the UCI Heart Disease Dataset to understand the relationship between health metrics—such as age, cholesterol levels, and maximum heart rate—and the presence of heart disease.

Key Objectives:
Data Cleaning & Preprocessing: Handling raw data for model readiness.

Exploratory Data Analysis (EDA): Understanding underlying trends and correlations.

Model Training: Implementing a classification model using the Logistic Regression algorithm.

Performance Evaluation: Assessing the model using Accuracy, Confusion Matrix, and ROC-AUC metrics.

🛠️ Tech Stack & Libraries
Language: Python 🐍

Libraries: * Pandas: For data manipulation and analysis.

Scikit-Learn: For model training, scaling, and evaluation.

Matplotlib & Seaborn: For data visualization and feature importance analysis.

📊 Methodology
1. Data Preprocessing
Label Encoding: Converted the Sex feature into a numerical format.

Feature Selection: Selected critical health features including Age, Sex, Resting BP, Cholesterol, Max HR, and Oldpeak.

Standard Scaling: Applied feature scaling to normalize the data and improve model convergence and accuracy.

2. Model Training
We implemented Logistic Regression, as it is a highly effective and interpretable algorithm for binary classification tasks (Predicting Disease vs. No Disease).

3. Evaluation Metrics
The model achieved the following performance results:

Accuracy Score: ~71.7%

ROC-AUC Score: ~0.716

Confusion Matrix:
| | Predicted: No | Predicted: Yes |
| :--- | :---: | :---: |
| Actual: No | 71 | 31 |
| Actual: Yes | 27 | 76 |

📈 Feature Importance Analysis
The visualization highlights which factors most significantly influence the prediction of heart disease:

Max Heart Rate: Shows a positive correlation (higher heart rates are often associated with positive diagnoses in this dataset).

Oldpeak & Sex: Show a negative correlation/impact according to the model's coefficients.
