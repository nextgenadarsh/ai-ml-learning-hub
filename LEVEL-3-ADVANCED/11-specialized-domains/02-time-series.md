# Time Series Analysis & Forecasting

## Overview
This module focuses on time series forecasting, feature engineering for temporal data, stationarity, ARIMA/Prophet, deep learning approaches (RNNs, LSTMs, Temporal Convolutional Networks), and evaluation metrics for forecasting.

## Learning Objectives
- Preprocess and visualize time series data
- Understand stationarity and perform differencing
- Implement ARIMA/SARIMA and Facebook Prophet models
- Build LSTM and TCN models for forecasting
- Evaluate forecasts using MAPE, RMSE, MAE
- Handle irregular time series and multivariate forecasting

## Notebooks / Sections
1. Time Series Fundamentals — decomposition, seasonality, trend
2. Classical Methods — ARIMA, SARIMA, model selection
3. Prophet — growth models, changepoints
4. Deep Learning — LSTM, Seq2Seq forecasting
5. Advanced Topics — multivariate forecasting, probabilistic forecasting

## Example: Simple LSTM with Keras
```python
import numpy as np
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import LSTM, Dense

# Synthetic data
x = np.sin(np.linspace(0, 100, 1000))
seq_len = 20
X, Y = [], []
for i in range(len(x)-seq_len):
    X.append(x[i:i+seq_len])
    Y.append(x[i+seq_len])
X = np.array(X).reshape(-1, seq_len, 1)
Y = np.array(Y)

model = Sequential([LSTM(32, input_shape=(seq_len,1)), Dense(1)])
model.compile(optimizer='adam', loss='mse')
model.fit(X, Y, epochs=5, batch_size=32)
```

## Exercises
- Forecast daily sales using ARIMA and LSTM and compare
- Build a multivariate forecast with exogenous variables
- Implement probabilistic forecasting using quantile regression

---

> Resources: link to datasets (M4, M3, electricity), and Prophet/TensorFlow docs.