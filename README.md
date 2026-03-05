# AI Stock Trend Predictor

A Machine Learning web application that predicts whether a stock will go UP or DOWN based on historical price data.

The app fetches real-time market data using Yahoo Finance and applies a Logistic Regression model to analyze stock trends.

## Features

- Predicts stock direction (UP or DOWN)
- Uses real-time stock data from Yahoo Finance
- Interactive Streamlit web interface
- Visualizes stock closing price trends
- Simple machine learning pipeline

## Tech Stack

Python  
Streamlit  
Scikit-learn  
Pandas  
yfinance  

## Machine Learning Model

Logistic Regression is used to classify stock movement.

Features used:
- Daily Return
- 5-Day Moving Average

## How It Works

1. User enters stock symbol (example: TCS.NS)
2. System downloads 1 year of historical data
3. Features are created from price data
4. Logistic Regression model is trained
5. Model predicts next-day stock direction

## Run the Project

Install dependencies
