Stock Price Prediction Using LSTM, 1DCNN, and Hybrid Architectures

Overview
This project focuses on predicting stock prices using three different deep learning architectures: LSTM, 1D Convolutional Neural Network (1DCNN), and a Hybrid LSTM+1DCNN model. Each model is evaluated based on its ability to predict stock prices and capture both short-term patterns and long-term dependencies in time series data.

Approach
1. LSTM Model
The LSTM model is designed to capture long-term temporal dependencies in stock price data.

It consists of multiple LSTM layers with progressively fewer units to refine feature extraction.

Dropout layers are added to prevent overfitting.

2. 1D CNN Model
The 1DCNN model extracts local patterns from the time series data using convolutional filters.

MaxPooling layers are used to reduce dimensionality and computational complexity.

Dropout layers are included for regularization.

3. Hybrid LSTM+1DCNN Model
This model combines the strengths of both LSTMs and CNNs.

LSTMs capture long-term dependencies, while CNNs extract short-term patterns.

The architecture includes both LSTM and Conv1D layers, followed by dense layers for final prediction


Instructions to Reproduce Results
Ensure you have the following installed:
Python 3.x
TensorFlow >= 2.x
NumPy
Matplotlib

****Casually run all the cells.
