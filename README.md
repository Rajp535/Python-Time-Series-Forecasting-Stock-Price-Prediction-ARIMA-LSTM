# 📈 Stock Price Prediction using ARIMA & LSTM

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/<your-repo>/blob/main/Stock_Price_Forecasting_using_ARIMA_&_LSTM.ipynb)

This project applies **classical statistical models (ARIMA)** and **deep learning models (LSTM)** to forecast stock prices.  
It demonstrates a complete **time series forecasting workflow** including data collection, exploratory analysis, stationarity checks, decomposition, and predictive modeling.

---

## 🚀 Project Overview

- **Dataset**: Stock price data from Yahoo Finance (e.g., `KOTAKBANK.NS`, `TATAMOTORS.NS`).
- **Models Implemented**:
  - ARIMA (AutoRegressive Integrated Moving Average)
  - LSTM (Long Short-Term Memory Neural Network)
- **Workflow**:
  1. Data loading & visualization
  2. ETS decomposition
  3. Stationarity checks (ADF test, differencing, ACF/PACF)
  4. ARIMA model fitting & forecasting
  5. LSTM model training & forecasting
  6. Comparison of actual vs. predicted results

---

## 📂 Repository Structure

├── Stock_Price_Forecasting_using_ARIMA_&_LSTM.ipynb # Main Jupyter/Colab notebook
├── README.md # Project documentation

## 🛠️ Installation & Requirements

Run this project on **Google Colab** (recommended).  

If running locally, install dependencies:
pip install pandas numpy matplotlib seaborn yfinance statsmodels scikit-learn tensorflow

## 📊 Results

### 🔹 ARIMA Model
- **RMSE:** 26.26  
- **MSE:** 689.57  
- **MAPE:** 2.46%  

### 🔹 LSTM Model
- **RMSE:** 55.92  
- **MSE:** 3127.17  
- **MAPE:** 6.65%

Example Output:

Time series decomposition

ACF/PACF plots

ARIMA forecast with confidence intervals

LSTM forecast vs actual prices

 ## 📌 Next Steps

Add more models (Prophet, XGBoost, Transformers)

Hyperparameter tuning for ARIMA (p,d,q) and LSTM layers

Deploy model via Streamlit / FastAPI for live stock prediction

 ## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

## 📜 License

This project is licensed under the MIT License.



