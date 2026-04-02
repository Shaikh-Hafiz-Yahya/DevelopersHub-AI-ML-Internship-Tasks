# 📈 Stock Price Prediction using Linear Regression (Tesla - TSLA)

This project focuses on predicting the future closing prices of **Tesla (TSLA)** stock by analyzing historical market data. The model is built using Python to demonstrate how market features like Open, High, and Low prices influence stock trends.

## 🚀 Project Overview
Stock market data is inherently volatile and non-linear. In this task, we implemented a **Linear Regression** algorithm to understand the statistical relationship between daily market features (Open, High, Low, Volume) and the next day's **Closing price**.

### Key Objectives:
* **Automated Data Retrieval:** Using `yfinance` to fetch real-time historical stock data.
* **Target Labeling:** Shifting the 'Close' price to create a supervised learning target.
* **Predictive Modeling:** Training a regression model to estimate future market values.
* **Performance Analysis:** Evaluating accuracy through R2 Score and error metrics.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 🐍
* **Core Libraries:**
    * `yfinance`: For fetching real-time historical financial data.
    * `Pandas`: For data cleaning, manipulation, and feature engineering.
    * `Scikit-Learn`: For data splitting, model training, and performance evaluation.
    * `Matplotlib` & `Seaborn`: For creating professional price trend visualizations.

---

## 📊 Methodology

### 1. Data Acquisition & Preprocessing
* **API Integration:** Extracted Tesla's historical dataset directly via the `yfinance` API.
* **Feature Engineering:** Created a `Target` column by shifting the 'Close' price, enabling the model to learn from historical patterns to predict future values.
* **Data Cleaning:** Handled missing values (NaN) using Pandas to ensure model stability and prevent calculation errors.

### 2. Model Training
* **Train-Test Split:** The dataset was divided into training and testing sets (80/20 ratio) to validate the model on unseen data.
* **Algorithm:** Applied **Linear Regression** to find the line of best fit for the stock's price trajectory.

### 3. Evaluation Results
The model demonstrated exceptional predictive capability:
* **$R^2$ Score:** **0.986** (Indicating high predictive accuracy for the given historical features).

---

## 📈 Visualizing Results
We utilized **Scatter Plots** and **Line Charts** to compare **Actual vs. Predicted** prices. These visualizations confirm that the model's predictions align closely with real market values, capturing the general momentum of Tesla's stock.



---

## 👨‍💻 Author
**Hafiz Muhammad Yahya**
*Undergraduate Student (BS AI) at SMIU*
* [LinkedIn](https://www.linkedin.com/in/hafiz-muhammad-yahya-02a8312b9/)
* [GitHub](https://github.com/m-yahya-05)
