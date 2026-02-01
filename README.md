# **Time series analysis on stock closing prices**

This repo is designed with the sole purpose to predict the time series of the [Tesla stock closing price](https://www.kaggle.com/datasets/varpit94/tesla-stock-data-updated-till-28jun2021), sourced from Kaggle. The work in this repository should give as much of an insight into the various methods used for time series forecasting in general. 

Time series forecasting can be performed by many techniques:
1. **Machine Learning**: GRUs (Gated Recurrent Unit) and LSTMs (Long-short term memory models) are examples of RNNs (Recurrent Neural Networks) that learn patterns while processing through sequences from historical data. These, together with transformers and other ML techniques, are preferred as ML models can handle nonlinear relationships easier and capture long-term dependencies for complex time series data.
2. **Statistical learning**: ARIMA (Autoregressive Integrated Moving Average) and its extension, SARIMA (Seasonal -ARIMA) are popular techniques. Exponential smoothing is better at short-term forecasting.
3. **Others**: Strong contenders for accurate time series forecasting include vector autoregression (VAR) and gaussian process regression (GPR). Using the open-sourced `Prophet` framework, developed by Meta, can also perform time series forecasting.

In fact, exponential smoothing and vector autoregressive models are special cases of ARIMA models.

Disclaimer: The number of methods and ways of tuning them for better performance metrics are exhaustive. This repository is continuously updated.
