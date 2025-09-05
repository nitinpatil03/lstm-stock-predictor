# Stock Price Prediction with LSTM

This project forecasts stock prices using a stacked LSTM model implemented with TensorFlow/Keras. The model trains on historical closing prices and predicts future stock prices.

## Features

- Fetches stock price data using `pandas_datareader` from Yahoo Finance or Tiingo.
- Preprocesses data with MinMax scaling.
- Uses stacked LSTM layers for time-series forecasting.
- Evaluates predictions with RMSE.
- Visualizes actual vs. predicted prices and forecasts future prices.
- Optional Flask app UI to interact with the model.

## Requirements

- Python 3.7+
- TensorFlow
- pandas_datareader
- numpy
- pandas
- scikit-learn
- matplotlib
- Flask (optional, for UI)

## Installation

```bash
pip install tensorflow pandas_datareader numpy pandas scikit-learn matplotlib Flask
