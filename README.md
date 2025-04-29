# NeoBrutalist Paper Trading App

## Overview
The **NeoBrutalist Paper Trading App** is a Python-based stock trading simulator designed to simulate the experience of trading stocks with a virtual balance. The application allows users to view stock prices, buy and sell shares, and manage their portfolio. The app provides a minimalistic, modern user interface built using `Tkinter`, and fetches stock data using the `yfinance` library. It also displays stock price charts using `matplotlib`.

## Features
- **Track Stock Prices**: Fetch real-time stock prices using Yahoo Finance API.
- **Buy and Sell Shares**: Users can buy or sell shares with a virtual balance.
- **Portfolio Management**: View and manage your stock portfolio with the ability to load and save progress.
- **Transaction History**: Keep track of all stock trading activities with timestamps.
- **Stock Charts**: Fetch and display 1-month historical stock price charts.
- **Persistent Data**: Save and load the portfolio using a JSON file.

## Requirements
- Python 3.x
- `yfinance`: Fetches real-time stock data.
- `matplotlib`: Plots stock price charts.
- `tkinter`: GUI library (usually included with Python installations).

To install the required dependencies, run the following command:
```bash
pip install yfinance matplotlib
