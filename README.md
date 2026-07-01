# 📈 Financial Asset & Return Analysis Project

A financial data analysis project that explores the historical performance, risk, and relationships between three major financial assets:

- **S&P 500**
- **NASDAQ**
- **Bitcoin**

Using Python and statistical analysis, this project evaluates asset returns, volatility, covariance, correlation, risk-adjusted performance, downside risk, and return distributions over historical market data.

---

## Project Overview

The objective of this project is to analyze and compare the behavior of traditional equity indices and cryptocurrency using financial statistics commonly applied in investment analysis.

The analysis covers:

- Historical market data
- Daily log returns
- Risk and volatility
- Asset correlations
- Sharpe Ratio
- Semivariance (Downside Risk)
- Distribution of returns

---

## Objectives

- Retrieve historical financial market data
- Calculate daily logarithmic returns
- Measure volatility using variance and standard deviation
- Examine relationships between assets using covariance and correlation
- Evaluate risk-adjusted performance using the Sharpe Ratio
- Measure downside risk using semivariance
- Analyze whether stock returns follow a symmetric distribution

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- yFinance

---

## Project Workflow

### 1. Data Collection

Historical market data was collected for:

- S&P 500
- NASDAQ
- Bitcoin

The project analyzes approximately five years of daily price data.

---

### 2. Data Cleaning & Preparation

The dataset was prepared by:

- Removing unnecessary columns
- Handling missing values
- Removing weekend null values
- Calculating daily logarithmic returns
- Preparing clean datasets for analysis

---

### 3. Summary Statistics

Computed descriptive statistics including:

- Mean return
- Median
- Minimum
- Maximum
- Quartiles
- Standard deviation

These statistics provide an overview of each asset's historical performance.

---

### 4. Risk Analysis

Volatility was measured using:

- Variance
- Standard Deviation

The analysis shows that:

- Bitcoin exhibits substantially higher volatility than the S&P 500 and NASDAQ.
- Traditional equity indices demonstrate relatively lower investment risk.

---

### 5. Covariance Analysis

A covariance matrix was generated to evaluate how the assets move relative to one another.

Key findings:

- All covariance values were positive.
- Positive covariance indicates that the assets generally move in the same direction.

---

### 6. Correlation Analysis

Pearson correlation coefficients were calculated to quantify the strength of relationships between asset returns.

Major observations include:

- Strong positive correlation between the S&P 500 and NASDAQ.
- Much weaker, though still positive, relationship between Bitcoin and the equity indices.

Scatter plots with regression lines were also created to visualize these relationships.

---

### 7. Sharpe Ratio

The Sharpe Ratio was calculated to compare risk-adjusted returns.

This metric evaluates how much return is generated for each unit of risk taken.

The analysis shows that:

- S&P 500 and NASDAQ achieved very similar Sharpe Ratios.
- Bitcoin produced a slightly lower risk-adjusted return despite its higher returns due to significantly greater volatility.

---

### 8. Semivariance (Downside Risk)

Unlike standard deviation, semivariance measures only downside risk.

The project demonstrates that:

- Bitcoin has considerably higher downside risk.
- S&P 500 and NASDAQ experience much smaller negative deviations from their average returns.

This provides a more realistic assessment of investment risk.

---

### 9. Return Distribution Analysis

Using a larger historical dataset (approximately 20 years), the project examines the statistical distribution of stock returns.

The analysis investigates:

- Return symmetry
- Skewness
- Distribution around the mean

This helps assess assumptions commonly used in financial modeling.

---

## Key Insights

- Bitcoin is significantly more volatile than traditional stock indices.
- S&P 500 and NASDAQ exhibit a very strong positive correlation.
- Bitcoin has only a moderate relationship with equity markets.
- Traditional indices provide stronger risk-adjusted performance.
- Bitcoin experiences substantially higher downside risk.
- Historical equity returns appear reasonably close to symmetric but exhibit slight negative skewness.

---

## Skills Demonstrated

- Financial Data Analysis
- Time Series Analysis
- Statistical Analysis
- Risk Analysis
- Investment Analytics
- Portfolio Metrics
- Data Cleaning
- Data Visualization
- Exploratory Data Analysis (EDA)
- Python Programming

---

## Possible Future Improvements

- Portfolio optimization using Modern Portfolio Theory
- Efficient Frontier visualization
- CAPM analysis
- Beta estimation
- Value at Risk (VaR)
- Monte Carlo portfolio simulation
- Portfolio backtesting
- Interactive dashboards using Plotly or Streamlit

---

## Example Analyses

The notebook includes visualizations and statistical analyses such as:

- Daily return plots
- Return distributions
- Scatter plots with regression lines
- Covariance matrix
- Correlation analysis
- Volatility comparisons
- Sharpe Ratio calculations
- Semivariance analysis

---

## Repository Structure

```
Financial-Asset-Return-Analysis/
│
├── Financial_Asset_&_Return_Analysis.ipynb
├── README.md
└── stock_return_data
```

---

## Conclusion

This project demonstrates practical financial analytics techniques for evaluating investment performance and risk. By comparing traditional equity indices with cryptocurrency, it highlights how statistical methods such as log returns, volatility, covariance, correlation, Sharpe Ratio, and semivariance can be used to better understand market behavior and support data-driven investment decisions.

---
