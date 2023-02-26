Stock_Price_Prediction

This project is a stock price prediction model built using Long Short-Term Memory (LSTM) algorithm. The LSTM model is a type of recurrent neural network (RNN) that is well-suited for making predictions based on time series data, such as stock prices.

Data

The model is trained on historical stock price data obtained from Yahoo Finance. The data includes the open, high, low, and closing prices of the stock you want to predict the price for, adjusted close prices as well as the volume of shares traded. The dataset covers a period of seven years, with daily data points.

LSTM Model

The LSTM model is built using Keras, a high-level neural networks API written in Python. The model consists of an input layer, several LSTM layers, and an output layer. The input layer takes in the historical stock price data, and the output layer produces a predicted stock price for the next day.

Results

The LSTM model has been shown to be effective at predicting future stock prices, with a mean squared error (MSE) of 0.0046. The predictions made by the model have been compared with the actual stock prices, and the results are promising.
