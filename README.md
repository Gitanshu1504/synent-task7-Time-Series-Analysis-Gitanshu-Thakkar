Project Title

Time Series Analysis on Stock Price Dataset

Problem Statement:

The objective of this project is to analyze stock price data over time to identify trends, detect seasonality, and optionally forecast future stock prices. Time series analysis helps investors and analysts understand historical performance and make informed decisions.

Dataset Details:

Dataset Name: Stock Price Dataset
File Format: CSV
Main Features:
Date
Open Value
High Value
Low Value
Last Value (Closing Price)
Turnover

Approach:

Loaded the stock price dataset using Pandas.
Converted the date column to datetime format and sorted the data.
Removed missing values from the last_value column.
Performed Trend Analysis using a line chart.
Calculated Monthly Average Stock Price to observe long-term trends.
Detected seasonality using a 30-day Moving Average.
Applied Linear Regression to generate a simple 30-day forecast (optional).
Visualized the results using Matplotlib.

Results:

The stock price trend shows how prices changed over time.
Monthly averages highlight long-term movement.
The moving average reduces daily fluctuations and reveals overall patterns.
The Linear Regression model provides a basic estimate of future prices.
These visualizations support better understanding of stock market behavior.
