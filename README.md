# Stock-Price-Analysis-for-Google-(GOOG)-yfinance

Historical Stock Price Analysis for Google (GOOG) from Aug 2004 to Nov 2024

Objective:
This notebook demonstrates how to fetch and analyze historical stock price data for Google (ticker symbol: GOOG) using the yfinance library. The analysis covers the period from August 4, 2004, to November 30, 2024. The notebook provides insights into how to download stock data, access important price metrics, and save the data for further analysis.

Key Steps in the Notebook:

Import Libraries:

The necessary libraries (pandas, yfinance, datetime) are imported to fetch and process the data.
Set Date Range:

The notebook defines the start and end dates for fetching stock data. It fetches data for the past 365 days but can be easily adjusted to a custom range. Here, the data from Aug 4, 2004 to Nov 30, 2024 is retrieved.
Fetch Stock Data:

Using the yfinance API, the notebook downloads daily stock prices for Google (GOOG). The historical data is retrieved from Yahoo Finance.
Data Inspection:

The notebook displays the first few rows of the data for quick inspection and prints the shape of the DataFrame to confirm the size of the dataset.
Extract Last Closing Price:

The last closing price of Google stock is extracted and displayed. This is useful to track the most recent price at the time of running the notebook.
Save the Data:

The data is saved as a CSV file for further use, allowing users to export and analyze the data offline or in other tools.
Intended Audience: This notebook is ideal for:

Data scientists and analysts looking to get started with stock price data analysis.
Investors and traders who wish to analyze historical stock price trends.
Anyone interested in learning how to use Python for financial data analysis using Yahoo Finance.
Future Enhancements:

Visualizations: Add charts to visualize the price trends, such as line plots of closing prices over time.
Technical Indicators: Calculate and plot key technical indicators like moving averages or Bollinger Bands.
Machine Learning: Implement predictive models to forecast future stock prices based on historical data.
