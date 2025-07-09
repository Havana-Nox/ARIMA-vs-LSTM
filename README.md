# Bitcoin Price Prediction Using ARIMA and LSTM

This repository contains the implementation code used in the paper:  
**"Regression-based Cryptocurrency Price Prediction Using ARIMA and LSTM Algorithms"**

## 📄 Description

The project compares two time series forecasting models — ARIMA and LSTM — for predicting daily Bitcoin closing prices. The analysis covers historical data from January 1, 2020 to January 1, 2025.

The implementation includes:
- Data preprocessing and normalization
- ARIMA modeling with parameter selection (ADF test, AIC minimization)
- LSTM model built using TensorFlow/Keras
- Training, testing, and evaluation with MAE and RMSE metrics
- Visualization of predictions vs actual prices

## 📁 Files

- `bitcoin_prediction.ipynb`: Jupyter Notebook with all code and results


## 🔧 Requirements

- Python 3.10+
- pandas, numpy, matplotlib, scikit-learn
- statsmodels
- TensorFlow / Keras

