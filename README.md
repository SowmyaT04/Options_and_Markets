# Options Strategies and Market Analysis

This repository contains assignments and practical work from an **Options Strategies and Market Analysis** course, covering options fundamentals, pricing models, Greeks, trading strategies, technical analysis, backtesting, and portfolio risk management through applied Python-based analysis.

Each assignment lives in its own folder with its own code, data, and notes. Only assignments that involve actual code are included — write-up/theory-only assignments are left out. Code is being cleaned up gradually (Assignment 2 is updated so far), so quality varies a bit across folders for now.

## 📚 What This Project Covers

### Options Fundamentals
- Call and put options, buyers and sellers
- Strike price, expiry, and option premium
- Intrinsic value vs. time value
- In-the-Money, At-the-Money, and Out-of-the-Money classification
- How options differ from futures and equity
- Option payoff and profit/loss calculations

### Option Pricing Models
- Black-Scholes-Merton (BSM) model
- Binomial option pricing (multi-step trees)
- American vs. European options
- Risk-neutral probabilities
- Comparing market price to theoretical fair value to flag over/underpriced options

### Option Greeks
- Delta, Gamma, Vega, and Theta
- How stock price, volatility, and time to expiry move each Greek
- Delta-neutral positioning and adjusting hedges as Delta changes
- Estimating time decay and volatility-driven price changes from Greeks

### Option Strategies
- Butterfly spreads
- Protective puts
- Long and short option combinations
- Option spreads for risk management
- Max Pain theory
- Strategy-level payoff analysis

### Market Data & Python
- Pulling market data with `yfinance`
- Working with stock and option-chain data
- Cleaning and preprocessing with Pandas
- Programmatically selecting ITM/ATM/OTM options
- Writing reusable functions for strategy payoffs
- Plotting historical and simulated price paths

### Simulation & Volatility
- Daily and annualized volatility from historical returns
- Monte Carlo simulation of future price paths
- Normal-distribution-based trading ranges (1st and 2nd standard deviation)
- Volatility-based stop-loss estimation

### Technical Analysis & Backtesting
- SMA, EMA, RSI, MACD, Bollinger Bands, Donchian Channel
- Generating buy/sell/hold signals
- Backtesting strategies with position and portfolio tracking
- Evaluating strategies with returns and Sharpe ratio

### Portfolio & Risk Management
- Daily asset returns and correlation matrices
- Building a diversified, low-correlation portfolio
- Portfolio weights and combined portfolio returns
- Historical simulation Value at Risk (VaR) at 95% confidence
