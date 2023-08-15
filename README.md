# Stock Prediction App using Streamlit and Prophet

This is a simple web application that predicts stock prices using the Prophet forecasting model. The app is built using the Streamlit framework and allows users to input a stock symbol, select the number of years for prediction, and visualize both historical and forecasted stock prices.

# Features

1) User-friendly interface for predicting stock prices.

2) Interactive sliders and text input for selecting the stock symbol and prediction period.

3) Displays historical stock data and plots raw open and close prices.

4) Utilizes the Prophet forecasting model to predict future stock prices.

5) Visualizes forecasted stock prices and their components.

6) Caches data loading to improve app performance.

# Installation

To run this app locally, follow these steps:

1) Clone this repository:

   "git clone https://github.com/AnuragASC/stock-prediction-app.git"
   "cd stock-prediction-app"

2) Create a virtual environment (recommended):

   "python -m venv venv"
   "source venv/bin/activate  # On Windows: venv\Scripts\activate"

3) Install the required dependencies:

   "pip install -r requirements.txt"

4) Run the Streamlit app:

   "streamlit run app.py"

5) Access the app in your web browser by opening the provided URL (usually http://localhost:8501).

# How to Use

1) Open the app in your web browser after running the streamlit run app.py command.

2) Enter the stock symbol you want to predict in the text input field.

3) Use the slider to select the number of years for prediction.

4) The app will display the historical data, raw price plots, forecast data, and forecast components.

5) Explore the visualizations and insights provided by the app.

# About Prophet

Prophet is an open-source forecasting tool developed by Facebook's Core Data Science team. It is designed for forecasting time series data with strong seasonal effects and multiple seasonality. The app uses the Prophet model to generate forecasts based on historical stock price data.

# Note

1) This app relies on external libraries such as Streamlit, yfinance, and Prophet. Make sure you have these libraries installed before running the app.
2) The app fetches stock data from the Yahoo Finance API using the yfinance library. Keep in mind that the availability and accuracy of this data may vary.
