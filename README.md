
# Algorithmic Trading: Technical Indicators & Twitter Sentiment

This repository contains an end-to-end algorithmic trading pipeline that integrates traditional technical analysis (**Bollinger Bands**, **MACD**) with alternative social media data. The project backtests these strategies against the S&P 500 to evaluate risk-adjusted returns.

## 📈 Performance Highlights

* **Bollinger Bands Strategy:** 17.8% Annual Return.
* **MACD Strategy:** 17.0% Annual Return.
* **Benchmark (S&P 500):** 9.11% Annual Return.

---

## 🚀 Getting Started

If you want to run this analysis on your local machine, follow these steps:

### 1. Prerequisites

Ensure you have **Python 3.8+** installed. Using a virtual environment or Anaconda is highly recommended.

### 2. Installation

Clone the repository and install the required dependencies:

```bash
# Clone the repository
git clone https://github.com/ritvi3601/algorithmic-trading.git
cd algorithmic-trading

# Install libraries
pip install yfinance pandas matplotlib pandas_datareader scipy statsmodels numpy

```

### 3. Required Libraries

| Library | Usage |
| --- | --- |
| **yfinance** | Scrapes historical market data from Yahoo Finance. |
| **pandas** | Data manipulation and time-series analysis. |
| **mplfinance** | Financial charting (Candlesticks/OHLC). |
| **statsmodels** | Statistical validation of signals. |

---

## 💻 How to Run

The entire analysis is self-contained within the Jupyter Notebook.

1. Launch Jupyter Notebook: `jupyter notebook`
2. Open **[pds_project.ipynb](https://github.com/ritvi3601/algorithmic-trading/blob/main/pds_project.ipynb)**.
3. **Run All Cells:** The notebook will fetch the latest ticker data and generate performance visualizations automatically.

---

## 🛠️ Methodologies

* **Technical Strategy:** Uses Bollinger Bands to identify volatility breakouts and MACD crossovers to confirm trend momentum.
* **Sentiment Analysis:** Analyzes Twitter engagement ratios (likes/comments/volume) to filter out "noise" and identify stocks with genuine social momentum.

---

## 🔮 Future Roadmap

To evolve this project into a robust trading system, the following updates are planned:

### 1. Advanced Machine Learning

* Implement **LSTM (Long Short-Term Memory)** networks for price sequence prediction.
* Develop **Reinforcement Learning** agents to optimize trade execution.

### 2. Live Deployment

* Integrate with the **Alpaca API** for real-time paper trading.
* Deploy as a 24/7 bot using **AWS EC2** or Google Cloud Functions.

### 3. Enhanced Sentiment

* Upgrade to **BERT or VADER NLP** models for deeper sentiment scoring of news headlines and Reddit threads.

---

## 📂 Project Structure

* `pds_project.ipynb`: The main [Jupyter Notebook](https://github.com/ritvi3601/algorithmic-trading/blob/main/pds_project.ipynb) containing code and results.
* `README.md`: Project documentation.
* `data/`: (Optional) Folder for cached CSV files like `Buy_profit.csv`.
