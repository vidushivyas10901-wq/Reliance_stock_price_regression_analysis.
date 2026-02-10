# Reliance_stock_price_regression_analysis.
**Project Overview**
This project focuses on analyzing historical stock data using Python and machine learning techniques. The goal is to provide actionable insights into short-term price movements and demonstrate practical data analytics skills in financial datasets.

**Features**
Data Cleaning & Preparation:
1.Handles missing values and removes junk rows (e.g.NaN, repeated ticker rows).
2.Converts date columns to datetime and numeric columns to correct types.

Exploratory Data Analysis (EDA):
1.Examines stock patterns, correlations between Open, High, Low, Close, and Volume.
2.Visualizes trends and relationships to understand market behavior.

Model Evaluation:
1.Metrics like R² score and Mean Squared Error (MSE) assess predictive accuracy.
2.Visualizations compare actual vs predicted closing prices for better interpretability.

**Finding**
R2_score is close to 1,therefore model is a good fit.
MSE = 28.87, the square root of this will be ~ 5.37(approx) on average share price variation.

**Insights:**
Highlights key drivers of stock price movements.
1.Provides a simple, reproducible workflow for predicting short-term stock prices.
2.Technologies & Libraries

Python 3.x
Pandas for data manipulation
NumPy for numerical computations
Scikit-learn for regression modeling
Matplotlib for data visualization

**Project Workflow**
> Data Collection: Download historical stock data (OHLC + Volume) from Yahoo Finance.
> Data Cleaning: Remove junk rows, convert data types, handle missing values.
> Feature Engineering: 
Train-Test Split: Split data for model training and evaluation.
Modeling: Train Linear Regression to predict closing price.
Evaluation & Visualization: Compare predicted vs actual prices using R², MSE, and scatter plots.

**Key Takeaways**
Predictive modeling can capture short-term stock price movements with historical OHLC (open,high,low,close) data.
Even with high R², real-world stock forecasting is challenging due to market volatility.

**Future Improvements**
Incorporate Future predictions, time-series forecasting models (ARIMA, LSTM) for better prediction.
Include sentiment analysis from news & social media.


Author

Vidushi Vyas — Aspiring Data Analyst
