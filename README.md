# 📈 Stock Price Prediction using Hybrid ARIMA + LSTM

This project implements a **hybrid model** combining traditional **ARIMA** (AutoRegressive Integrated Moving Average) with **LSTM** (Long Short-Term Memory) neural networks to forecast stock prices. It aims to model both linear and non-linear patterns in financial time series data.

---

## 🧠 Project Overview

- 📦 Download historical stock data using `yfinance`
- 📊 Apply **ARIMA** to capture trend and seasonality
- 🧮 Calculate **ARIMA residuals**
- 🤖 Train an **LSTM** model on residuals to model non-linear components
- 📉 Combine both predictions for final output
- 📈 Evaluate using metrics like RMSE, MAPE, MASE

---

## 📁 Files

| File | Description |
|------|-------------|
| `main_model.py` | Core code implementing ARIMA + LSTM hybrid model |
| `requirements.txt` | List of required Python libraries |
| `README.md` | This file |

---

## 🛠️ Requirements

Install the dependencies with:

```bash
pip install -r requirements.txt
