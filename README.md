# Stock Market Analysis 📈 + Prediction using LSTM

## Overview
This project analyzes and predicts stock prices of technology companies (Apple, Amazon, Google, Microsoft) using historical stock data. It uses `yfinance` for data retrieval, `Seaborn` and `Matplotlib` for visualization, and LSTM neural networks for prediction.

## Getting the Data
The first step is to get the data and load it to memory. We will get our stock data from the Yahoo Finance website. Yahoo Finance is a rich resource of financial market data and tools to find compelling investments. To get the data from Yahoo Finance, we will be using yfinance library which offers a threaded and Pythonic way to download market data from Yahoo. Check this article to learn more about yfinance: [Reliably download historical market data from with Python](https://aroussi.com/post/python-yahoo-finance)
## Goals
- Analyze stock price changes over time.
- Calculate and visualize average daily returns.
- Determine moving averages.
- Analyze the correlation between different stocks.
- Assess Value at Risk (VaR).
- Predict future stock prices using LSTM.

## Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/ahmedburale/stock-market-analysis-prediction.git
