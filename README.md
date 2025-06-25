# Backtesting-with-python
# 📊 Stock Backtesting Engine (2024)

This project implements a basic stock trading **backtesting framework** in Python using historical stock data from Yahoo Finance. It allows you to define custom trading strategies (like MACD + RSI) and evaluate their performance based on portfolio value, returns, and risk metrics.

---

## Features

-  Historical data download using `yfinance`
-  Custom strategy support (e.g., MACD + RSI crossover)
-  Trade simulation with cash & holdings tracking
-  Equity curve visualization
-  Performance metrics:
  - Total Return
  - Annualized Return
  - Volatility
  - Sharpe Ratio

---

## Strategy Used

**MACD + RSI Combo:**
- **Buy** when:
  - MACD > Signal Line
  - RSI < 70
  - Both conditions hold for 3 consecutive days
- **Sell** when:
  - MACD < Signal Line
  - RSI > 30
  - Both conditions hold for 3 consecutive days

This filters noise and triggers trades only when both momentum and overbought/oversold conditions align.

---

## Files

| File | Description |
|------|-------------|
| `soc.ipynb` | Jupyter Notebook with full code: data fetch, strategy, backtesting, and plotting |
| `README.md` | You're reading it! Documentation of the project |

---

