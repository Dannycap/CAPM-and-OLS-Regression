# CAPM-and-OLS-Regression

This Python script analyzes the relationship between the S&P 500 Index (^GSPC) and the stock BIGPX using the Capital Asset Pricing Model (CAPM) and OLS-Regression. The script performs the following tasks:

Data Retrieval: Utilizes the pandas_datareader library to fetch historical stock price data from Yahoo Finance for the specified time period.

Data Preprocessing: Calculates the logarithmic returns of the stock prices and handles any missing values.

Visualization:

Plots the cumulative returns over time.
Creates a pairplot to visualize relationships between different variables.
Plots subplots to display the volatility of the S&P 500 Index and the stock BIGPX.
Fits a linear regression model and plots the regression line to show the relationship between the two variables.
CAPM Analysis: Implements the Capital Asset Pricing Model (CAPM) to analyze the relationship between the S&P 500 Index and the stock BIGPX. This involves:

Estimating the beta coefficient, representing the stock's sensitivity to market movements.
Performing ordinary least squares (OLS) regression analysis to further examine the relationship between the two variables.
