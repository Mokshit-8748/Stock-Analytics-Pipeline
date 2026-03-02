# Stock Market Portfolio Analysis — Tesla vs GameStop

## Project Overview

This project presents a comparative financial analysis of Tesla (TSLA) and GameStop (GME) using historical stock data. The objective is to evaluate performance, volatility, and risk-adjusted returns, and to assess whether diversification through portfolio construction improves overall investment efficiency.

The analysis combines Python-based data processing with an interactive Power BI dashboard to explore return dynamics, risk exposure, and portfolio behavior.

---

## Objectives

### Primary Objective

Compare TSLA and GME across:
- Total Return  
- Volatility  
- Risk-Adjusted Performance (Sharpe Ratio)  

### Strategic Objective

Evaluate whether a weighted portfolio:
- Improves Sharpe ratio  
- Reduces maximum drawdown  
- Stabilizes volatility  

---

## Dataset

- **Source:** Yahoo Finance (via yfinance API)  
- **Frequency:** Daily historical data  
- **Period:** 2025–2026  
- **Assets:** Tesla (TSLA), GameStop (GME)  

---

## Tools & Technologies

- Python (yfinance, pandas, numpy)  
- Google Colab  
- BigQuery  
- Power BI  
- DAX  

---

## Data Processing & Feature Engineering

### Data Extraction
Daily OHLC price data was extracted using the yfinance API.

### Data Cleaning
- Trading calendars aligned  
- Non-trading days handled  
- Missing values addressed  
- Data validated  

### Feature Engineering
The following metrics were computed:

- Daily Returns  
- Cumulative Returns  
- Rolling 30-Day Volatility  
- Annualized Sharpe Ratio (252 trading days)  
- Compound Annual Growth Rate (CAGR)  
- Maximum Drawdown  
- Correlation  
- Portfolio Returns (weighted allocation)  

---

## Dashboard Structure

The Power BI dashboard includes the following analytical sections:

### 1. Performance Analysis
- Total Return  
- CAGR  
- Growth of $1 Investment  

### 2. Risk Analysis
- Rolling Volatility  
- Risk vs Return Scatter  

### 3. Risk-Adjusted Performance
- Sharpe Ratio Comparison  

### 4. Drawdown Analysis
- Maximum Drawdown  
- Recovery Duration  

### 5. Portfolio Construction
- Correlation Analysis  
- Diversification Impact  
- Portfolio Growth Comparison  

---

## Key Findings

- GME delivered higher total return over the selected period.  
- GME exhibited higher volatility and risk clustering.  
- TSLA experienced deeper drawdown phases.  
- Correlation between TSLA and GME was low (0.16), enabling diversification benefits.  
- The blended portfolio provided smoother return dynamics relative to single-asset exposure.  

---

## Financial Concepts Applied

- Portfolio Diversification  
- Risk-Return Tradeoff  
- Sharpe Ratio  
- Volatility Modeling  
- Drawdown Analysis  
- Compounded Growth  


