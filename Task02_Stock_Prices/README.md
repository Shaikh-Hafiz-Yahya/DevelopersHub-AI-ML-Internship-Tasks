📈 Stock Price Prediction using Linear Regression
This project focuses on predicting the future closing prices of Tesla (TSLA) stock by analyzing historical data. The model is built using Python and the yfinance library to demonstrate how market features influence stock trends.

🚀 Project Overview
Stock market data is inherently volatile. In this task, we implemented a Linear Regression algorithm to understand the relationship between features like Open, High, Low, and Volume and the next day's Close price.

🛠️ Tech Stack
Language: Python

Libraries: * yfinance: For fetching real-time historical stock data.

pandas: For data manipulation, cleaning, and feature engineering.

scikit-learn: For splitting data, training the Linear Regression model, and performance evaluation.

matplotlib & seaborn: For creating professional data visualizations.

📊 Methodology
Data Acquisition: Extracted Tesla's historical dataset using the yfinance API.

Feature Engineering: Created a Target column by shifting the 'Close' price, allowing the model to learn from future values.

Data Preprocessing: Handled missing values (NaN) using pandas to ensure high model stability.

Model Training: Split the dataset into training and testing sets (80/20 ratio) to validate the model's performance.

Evaluation: The model achieved an impressive R2 Score of 0.986, indicating high predictive accuracy for the given features.

📈 Visualizations
We utilized Scatter Plots to compare Actual vs. Predicted prices. These plots help in visualizing how closely the model's predictions align with the real market values.
