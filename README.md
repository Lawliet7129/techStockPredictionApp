# Stock Prediction App

## Overview

This Stock Prediction App is designed to forecast the future stock prices of selected companies using historical data and predictive modeling. The app leverages Streamlit for the user interface, Yahoo Finance for fetching historical stock data, and Facebook's Prophet for forecasting.

## Installation

To run this app locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
    ```
   
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
   
3. Run the app:
   ```bash
   streamlit run app.py
   ```

## File Structure

app.py: The main application script.
requirements.txt: Lists all the dependencies required to run the app.

## Dependencies:
The app relies on the following libraries:

Streamlit
yfinance
Prophet
plotly

To install these dependencies, run:
   ```bash
   pip install streamlit yfinance prophet plotly
   ```
## Usuage
1. Select Dataset for Prediction: Choose a stock ticker from the dropdown menu. Available options are:
Apple (AAPL)
Google (GOOG)
Microsoft (MSFT)
Uber (UBER)
Cisco (CSCO)
Intel (INTC)
Nvidia (NVDA)
Broadcom (AVGO)
Adobe (ADBE)
Taiwan Semiconductor (TSM)

2. Years of Prediction: Use the slider to select the number of years for which you want to predict stock prices (1 to 4 years).
3. Loading Data: The app will load the historical data for the selected stock from Yahoo Finance.
4. Raw Data Display: View the raw data table at the bottom of the page.
5. Time Series Plot: The app will display a time series plot of the stock's opening and closing prices.
6. Forecasting: The app will use Prophet to fit a model to the historical data and make predictions for the selected period. The forecast data and its components will be displayed.


   
