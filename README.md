# Time Series Forecasting with Hybrid Models

This project involves time series forecasting for stock prices using a hybrid approach combining ARIMA and LSTM models.

## Overview

The project utilizes historical stock data from 'GOOG.csv' and employs the following steps:

1. **Data Preprocessing**
   - Visualize the original closing prices.
   - Make the data stationary by taking the first difference.
   - Analyze Fourier Transform to check for stationarity.

2. **Autocorrelation Analysis**
   - Use ACF and PACF plots to determine model parameters (p, d, q) for ARIMA.

3. **ARIMA Modeling**
   - Fit an ARIMA model on the training data using identified parameters.
   - Forecast stock prices on the test data.
   - Plot the original test data and forecasted values.

4. **Error Analysis**
   - Calculate prediction errors between actual and forecasted values.
   - Visualize prediction errors.

5. **LSTM Modeling for Error Prediction**
   - Train an LSTM model on the errors from the ARIMA model.
   - Create sequences of errors for training the LSTM model.

6. **LSTM Model Training**
   - Build and train an LSTM model to predict errors.
   - Evaluate the performance of the LSTM model.

7. **Overall Prediction**
   - Combine ARIMA and LSTM predictions to get the final forecast.

## Requirements

- Python 3.x
- Libraries: TensorFlow, Statsmodels, Pandas, NumPy, Matplotlib, Scikit-learn
- One might require to download the tensorflow library as it is not inbuilt in base kernel

## Results
 - The project aims to predict stock prices using a hybrid ARIMA-LSTM model.
 - The performance of the model can be evaluated through visualizations and metrics.
## Acknowledgments
 - The project is a part of the WIDS workshop (Winter in Data Science)
 - Yahoo Finance for their historical data regarding stock prices
                                          
