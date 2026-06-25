# Financial Market Analysis

## Overview

This project explores the performance and risk characteristics of publicly traded U.S. companies using NYSE company data and historical stock prices obtained through Yahoo Finance.

The analysis focuses on understanding market structure, stock performance, return behavior, and the relationship between investment risk and reward through exploratory data analysis and financial metrics.

---

## Objectives

* Analyze the composition of companies listed on the NYSE.
* Explore sector and industry distributions.
* Retrieve and evaluate historical stock market data.
* Calculate and compare stock returns.
* Measure and visualize market risk using volatility.
* Examine the relationship between risk and expected return.

---

## Dataset

### NYSE Companies Dataset

The dataset contains information about publicly traded companies, including:

* Ticker Symbol
* Company Name
* Sector
* Industry
* IPO Year

### Historical Market Data

Historical stock price data was collected using the Yahoo Finance API and includes:

* Open Price
* High Price
* Low Price
* Close Price
* Adjusted Close Price
* Trading Volume

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Yahoo Finance (yfinance)
* Jupyter Notebook

---

## Analysis Performed

### Exploratory Data Analysis

* Data cleaning and preprocessing
* Missing value assessment
* Sector distribution analysis
* Industry distribution analysis
* Company listing trends

### Financial Analysis

* Historical stock price retrieval
* Daily return calculations
* Monthly return analysis
* Volatility measurement
* Risk-return comparison
* Market performance visualization

---

## Key Visualizations

The project includes visualizations such as:

* Sector distribution charts
* Historical stock price trends
* Daily return distributions
* Volatility comparisons
* Risk vs. Return scatterplots

---

## Key Findings

* Company representation varies significantly across sectors and industries.
* Stock performance differs considerably among firms and sectors.
* Investments with higher expected returns often exhibit greater volatility.
* Risk-return analysis provides valuable insight into investment decision-making.

---

## Repository Structure

financial-market-analysis/

├── data/
│   └── nyse.csv

├── notebooks/
│   └── finance_analysis.ipynb

├── images/

├── reports/

├── README.md

└── requirements.txt

---

## Future Enhancements

Potential extensions to this project include:

* Portfolio optimization using Modern Portfolio Theory
* Sharpe Ratio and risk-adjusted performance analysis
* CAPM implementation
* Efficient Frontier visualization
* Interactive dashboards using Streamlit or Tableau

---

## Author

Developed as part of a financial data analytics portfolio demonstrating skills in:

* Data Cleaning
* Exploratory Data Analysis
* Financial Analytics
* Time Series Analysis
* Data Visualization
* Python Programming
