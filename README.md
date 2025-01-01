# Stock_Price_Prediction

This project focuses on predicting stock prices using **Long Short-Term Memory (LSTM)** neural networks. The model analyzes historical stock data and forecasts the next day's stock price based on a sequence of previous days.

## Features
- **Exploratory Data Analysis (EDA)**:
  - Visualizations of stock price trends and volume.
  - Analysis of correlations, outliers, and anomalies.
- **Technical Indicators**:
  - Moving Averages (50-day, 200-day).
  - Bollinger Bands.
  - Volatility measures like Average True Range (ATR).
- **Data Scaling and Sequence Preparation**:
  - Scaled data using Min-Max normalization.
  - Generated sequences for LSTM input.
- **Deep Learning Model**:
  - Built and trained an LSTM model to predict stock prices.
  - Early stopping mechanism to prevent overfitting.
- **Performance Metrics**:
  - Calculated Root Mean Squared Error (RMSE) and R² scores.
- **User Interaction**:
  - Accepts a user-provided date to predict the stock price for the next trading day.

## Dataset
- **Source**: `Nifty50(15-24).csv` (contains daily stock data such as Open, High, Low, Close, Volume, etc.)
- **Columns**:
  - `Date`: Trading date.
  - `Open`, `High`, `Low`, `Close`: Stock prices.
  - `Turnover (₹ Cr)`, `Shares Traded`: Trading volume and turnover.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stock_price_prediction.git
   cd stock_price_prediction
