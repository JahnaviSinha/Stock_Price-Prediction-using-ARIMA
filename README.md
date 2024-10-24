# Stock_Price-Forcasting-using-ARIMA
This repository includes code for forecasting stock prices using the ARIMA model. The model was applied to three stocks: EXX5, IQQE, and IUS4, with data collected from Yahoo Finance for the period from May 2021 to May 2022.

# Key Steps in the Code
Library Imports
The code begins by importing essential libraries such as pandas, numpy, matplotlib, and statsmodels.

# Data Collection
Stock data from Yahoo Finance (May 2021 - May 2022) is loaded into a pandas dataframe for analysis.

# Data Preprocessing
Data is preprocessed by checking for missing values, converting to log-returns, and ensuring the time series is stationary.

# Model Selection
Using the statsmodels library, the ARIMA model is fitted to the stationary data. Model parameters are chosen via the auto_arima function.

# Model Fitting and Forecasting
The ARIMA model is then fitted to the data, and forecasts are generated for future stock prices. The model's performance is assessed using mean absolute error (MAE).

# Results Visualization
The code visualizes both the original and forecasted stock prices for comparison.

# Conclusion
This repository offers a basic implementation for stock price forecasting using ARIMA. It serves as a foundation for further exploration and model improvements.






