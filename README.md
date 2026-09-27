# Goldman Sachs (GS) Stock Price Prediction

A machine learning project that predicts the next-day closing price of Goldman Sachs (GS) stock using historical price data and technical indicators.

## 📊 Project Overview
This project uses Linear Regression to predict the next-day closing price of GS stock based on:
- Historical closing prices (5 years of data, 2020–2026)
- Technical indicators (moving averages)

## 🛠️ Tech Stack
- **Python**
- **yfinance** – for fetching historical stock data
- **pandas, numpy** – data processing
- **matplotlib** – visualization
- **scikit-learn** – model building and evaluation

## 📈 Features Used
- 7-day moving average (MA7)
- 30-day moving average (MA30)
- Previous day's closing price

## 🔍 Methodology
1. Downloaded 5 years of GS stock data using the `yfinance` API
2. Engineered features (moving averages, lag features)
3. Split data into training (80%) and testing (20%) sets — preserving time-series order
4. Trained a Linear Regression model
5. Evaluated performance using RMSE and R² score
6. Visualized actual vs predicted prices

## ✅ Results
- **RMSE:** 17.22
- **R-squared score:** 0.98

The model closely tracks actual price movements, as shown in the actual vs predicted price chart.

## 🚀 How to Run
1. Open the notebook in Google Colab (badge below)
2. Run all cells sequentially
3. View the results and visualizations at the end

[

![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)

](https://colab.research.google.com/github/GauriNehe/goldman-sachs-stock-prediction/blob/main/goldman-sachs-stock-prediction.ipynb)

## 📌 Note
This project is for educational purposes and should not be used for actual financial/investment decisions.
