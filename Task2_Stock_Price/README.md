# Task 2: Stock Price Prediction

## Objective
Use historical stock data to predict next day Apple closing price.

## Dataset
- **Name:** Apple (AAPL) Stock Data
- **Source:** Yahoo Finance via yfinance library
- **Period:** January 2020 — December 2024

## Models Applied
- Linear Regression
- Random Forest Regressor (100 trees)

## Key Results & Findings
- Random Forest outperformed Linear Regression on all metrics
- Previous day closing price is the strongest predictor
- Moving averages (MA_5, MA_20) were highly influential features
- shuffle=False critical for time series data integrity