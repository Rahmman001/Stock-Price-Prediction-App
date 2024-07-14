# Stock Prediction App [Demo Link](https://stock-price-predictor-main.streamlit.app)

This project is a Stock Prediction App built using Streamlit, Prophet, yFinance, and Plotly. The app allows users to select a stock and predict its future prices based on historical data. It includes interactive visualizations for better data analysis and understanding.

## Features

- **Stock Selection**: Choose from a list of popular stocks such as Apple (AAPL), Google (GOOG), Microsoft (MSFT), GameStop (GME), and Meta (META).
- **Data Loading**: Fetch historical stock data using yFinance.
- **Data Display**: View raw stock data in a tabular format.
- **Interactive Plots**: Visualize stock opening and closing prices with interactive Plotly charts.
- **Forecasting**: Predict future stock prices using Prophet and display the forecasted data.
- **Forecast Components**: Analyze forecast components such as trend, weekly, and yearly patterns.

## Installation

To run this project, you need to have Python installed on your system. Install the required packages using pip:

```bash
pip install streamlit fbprophet yfinance plotly
