
# Algorithmic Trading Strategy: Bollinger Bands, MACD & Twitter Sentiment

## 📌 Project Overview

This project explores the implementation and effectiveness of algorithmic trading strategies in modern financial markets. By leveraging mathematical indicators and alternative data (social media sentiment), the system identifies entry and exit points to maximize profitability while smoothing out market noise.

## 📈 Performance Results

The strategies were backtested against the S&P 500 (9.11% average return) with the following results over the past year:

| Strategy | Annual Return | vs. S&P 500 |
| --- | --- | --- |
| **Bollinger Bands** | **17.8%** | +8.69% |
| **MACD** | **17.0%** | +7.89% |
| **S&P 500 (Benchmark)** | **9.11%** | -- |

## 🛠️ Methodologies

### 1. Technical Indicators

* **Bollinger Bands:** Utilized to identify overbought/oversold conditions and volatility breakouts. The strategy tracks price action relative to standard deviation bands around a Simple Moving Average (SMA).
* **MACD (Moving Average Convergence Divergence):** Used for trend identification and signal generation through bullish/bearish crossovers.

### 2. Alternative Data: Twitter Analysis

An innovative layer of the project involves analyzing **Social Media Influence**. By tracking:

* Engagement Ratios (Likes/Comments)
* Post Volume
* Sentiment Trends
The model compares the performance of "high-engagement" stocks against those with low social media activity to find correlations between digital hype and price movement.

## 📂 Implementation Details

* **Data Processing:** Meticulous calculation of buy/sell signals recorded via Excel and Python.
* **Risk Management:** Focused on dynamic support/resistance levels and trend confirmation to mitigate potential losses.
* **References:** Insights drawn from *Quantitative Finance* (Paul Wilmott) and *Quantitative Trading* (Ernie Chan).

## 🚀 Future Recommendations

* **Fine-tuning:** Continuous optimization of DAX/Python scripts for better risk-adjusted returns.
* **Machine Learning:** Integrating ML models to further refine the Twitter sentiment analysis.
* **Diversification:** Expanding the strategy across multiple asset classes beyond the S&P 500.
