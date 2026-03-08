
# Algorithmic Trading Strategy: Bollinger Bands, MACD & Twitter Sentiment

## 📌 Project Overview

This project explores the implementation and effectiveness of algorithmic trading strategies in modern financial markets. By leveraging mathematical indicators and alternative data (social media sentiment), the system identifies entry and exit points to maximize profitability while smoothing out market noise.

1. Prerequisites
Ensure you have Python (3.8 or higher) and Anaconda (recommended) installed.2. Clone the RepositoryBashgit clone https://github.com/ritvi3601/algorithmic-trading.git
cd algorithmic-trading
3. Install Required LibrariesThe project relies on several key quantitative and financial libraries. You can install them all at once using pip:Bashpip install yfinance pandas pandas_datareader matplotlib mplfinance scipy statsmodels numpy
LibraryPurposeyfinanceScrapes historical market data from Yahoo Finance.pandasData manipulation and time-series analysis.mplfinanceSpecialized financial charts (candlesticks, OHLC).statsmodelsStatistical modeling and hypothesis testing.scipyScientific computing and technical indicators.📈 Analysis OverviewThe core logic is contained within the pds_project.ipynb notebook. The project explores three main strategies:Moving Average Price Action: Implementing short-term (5-day) vs. long-term (30-day) EMA crossovers to determine Buy/Sell positions.Bollinger Bands: Calculating volatility-based bands to identify overbought and oversold conditions.Sentiment-Based Trading: Integrating Twitter sentiment data (engagement ratios, likes, and comments) to correlate social media buzz with stock movement.💻 How to RunLaunch Jupyter Notebook or JupyterLab:Bashjupyter notebook
Open pds_project.ipynb.Run the cells sequentially. The data fetching is automated via yfinance, so you don't need to provide external CSVs for the price action sections.📊 Key Metrics TrackedCumulative Returns: Total growth of the investment over the backtesting period.Annualized Sharpe Ratio: Risk-adjusted return metric to evaluate strategy efficiency.Strategy vs. Buy & Hold: Direct comparison of the algorithmic strategy against a passive investment approach.

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
