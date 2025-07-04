# 📈 Stock Market Forecasting and Investment Strategy Optimization

**Bachelor’s Integrative Project (PIC1)**  
Author: Pedro Maltez  
Date: 2025

## 💡 Overview

This project analyzes the S&P 500 index using historical data, applies statistical models (logarithmic regression and Monte Carlo simulations), and compares fixed vs. dynamic monthly investment strategies. The core objective is to improve upon the traditional *Buy and Hold* approach by identifying undervalued and overvalued market conditions.

## ⚙️ Technologies and Libraries

- **Python**
- **Pandas** and **NumPy** – Data handling
- **Matplotlib** – Visualizations
- **yFinance** – Market data
- **Custom Modules** – `plotter.py`, `helper.py` for visual and simulation support
- **Jupyter Notebook** – [Full notebook](Data_Analysis/results.ipynb)



## 📊 Features

- **Logarithmic Regression** on historical S&P 500 prices
- **Dynamic Monthly Allocation** based on valuation vs. trendline
- **Monte Carlo Simulations** with Geometric Brownian Motion
- **ROI Comparison** between:
  - Static monthly investments (*Buy and Hold*)
  - Dynamic allocation based on valuation signals
- **Filtered Results** using percentile thresholds (25th–75th)

## 📁 Project Structure

```
.
├── Data_Analysis/
│   ├── S&P500_Data/        # Pickled data
│   ├── aux_functions/
│   │   ├── plotter.py      # Plotting tools
│   │   └── helper.py       # Simulations & helpers
├── backtest_&_montecarlo.py          # Main analysis script
└── README.md               # This file
```

## 📈 Sample Outputs

- S&P 500 vs. exponential regression curve ![S&P 500 vs. exponential regression curve](Data_Analysis/results/exp_vs_sp500.png)
- Histogram of investment allocation ![Histogram of investment allocation](Data_Analysis/results/total_allocation_maltez.png)
- Comparison of portfolio growth ![Comparison of portfolio growth](Data_Analysis/results/historical_sp500_vs_maltez.png)
- ROI histograms from simulations ![ROI histograms from simulations](Data_Analysis/results/roi.png)

## 📌 Key Results

- The S&P 500 follows an exponential long-term trend.
- Dynamic strategies yielded higher median ROI in most cases.
- Monte Carlo simulations introduced robustness and confidence ranges for ROI.

## 📬 Contact

**Pedro Maltez**  
[LinkedIn](https://www.linkedin.com/in/pedro-maltez-48a70915a/)  
[Email](mailto:pedromaltez16.1@gmail.com)
