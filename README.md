# Nvidia Time Series Forecasting
Status: Completed

This project analyzes and forecasts Nvidia (NVDA) stock prices using statistical time series models to evaluate trend behavior, volatility patterns, and financial risk.

---

## Project Overview

- Uses daily NVDA stock data (Jan 2022 – Sept 2024)
- Forecasts price movement using **ARIMA/SARIMA**
- Models volatility behavior using **GARCH**
- Evaluates models using AIC/BIC, stationarity tests, and diagnostic analysis
- Compares trend vs volatility modeling to assess forecast reliability and risk

---

## Key Findings

- **ARIMA(1,1,1)** captures short-term price trend but does not model volatility changes
- **GARCH(1,1)** effectively models volatility clustering and market risk behavior
- Rising volatility over time leads to higher forecast uncertainty
- Combining trend and volatility models provides deeper insight than price forecasting alone

---

## Data

- Source: Yahoo Finance NVDA historical stock data (via Kaggle)
- Time Period: **January 2022 – September 2024**
- Includes: Open, High, Low, Close, Adjusted Close, Volume

---

## Tools & Methods

- R for statistical modeling and analysis
- SARIMA for trend forecasting
- GARCH for volatility modeling
- Stationarity tests (ADF), ACF/PACF, residual diagnostics
- Libraries: `forecast`, `astsa`, `tseries`, `fGarch`, `ggplot2`

---

## Project Takeaways

- Forecasting stock price direction requires different methods than forecasting risk
- Volatility modeling is essential in financial time series analysis
- NVDA exhibits strong volatility clustering, making GARCH a strong fit for risk assessment

---

## Status

Completed and included for portfolio purposes.
