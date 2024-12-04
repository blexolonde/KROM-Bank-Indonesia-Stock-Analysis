## KROM Bank Indonesia Stock Historical Price Analysis

### Project Overview

This project analyzes the historical stock prices of KROM Bank Indonesia to identify trends, patterns, and insights. The analysis covers daily, weekly, and monthly stock data to assist investors, traders, and financial analysts in making informed decisions.

---

### Dataset Description

The project utilizes three datasets sourced from [Kaggle - KROM Bank Indonesia Stock Historical Price](https://www.kaggle.com/datasets/caesarmario/krom-bank-indonesia-stock-historical-price):

- **Daily Stock Prices (BBSI.JK.csv)**  
  A dataset containing 1,028 entries of daily stock prices.  
  Columns: Date, Open, High, Low, Close, Adj Close, Volume.

- **Weekly Stock Prices (BBSI.JK_weekly.csv)**  
  A dataset containing 222 entries of weekly aggregated stock prices.  
  Columns: Same as the daily dataset.  
  **Note**: There are some missing values, including a gap on April 7th, 2024, which is likely due to a holiday.

- **Monthly Stock Prices (BBSI.JK_monthly.csv)**  
  A dataset containing 51 entries of monthly aggregated stock prices.  
  Columns: Same as the daily dataset.
---
### Goals of the Analysis

- **Explore Stock Trends**  
  Analyze and visualize stock price trends and trading volumes across daily, weekly, and monthly data.

- **Assess Risk and Performance**  
  Calculate returns, volatility, and other key performance metrics.  
  Perform risk analysis using historical stock price data.

- **Identify Patterns and Opportunities**  
  Detect seasonal trends and significant patterns in stock performance.  
  Identify optimal periods for buying and selling.

- **Predict Future Trends**  
  Build predictive models using time-series analysis to forecast future stock prices.
---
### Key Business Questions

- How do stock prices and trading volumes vary across different timeframes (daily, weekly, monthly)?
- What is the historical volatility and risk-return profile of the stock?
- Are there specific times (e.g., months or weeks) with consistent stock performance trends?
- Can historical data be used to predict future stock prices or trends?
- How do adjusted closing prices compare to actual closing prices?
---
### Steps to Reproduce the Analysis

1. **Exploratory Data Analysis**  
   - Compare close prices across daily, weekly, and monthly timeframes using visualizations.  
   - Analyze trading volumes over time to detect patterns or anomalies.  

2. **Performance Metrics**  
   - Compute key metrics such as daily returns, volatility, and annualized volatility.  
   - Use rolling returns to observe and analyze trends over time.  

3. **Specific Time Trends**  
   - Identify average monthly performance to uncover seasonal trends or recurring patterns.  

4. **Forecasting**  
   - Implement an ARIMA model for short-term price forecasting.  

5. **Adjusted vs Actual Close Prices**  
   - Plot and compare raw close prices with adjusted close prices (if available) to understand discrepancies.  

### Technologies Used

- **Programming Language**: Python
- **Libraries**: pandas, matplotlib, seaborn, statsmodels, scikit-learn
- **Tools**: Jupyter Notebook

### How to Use the Code

1. Clone the repository.
2. Install the necessary Python libraries (using `requirements.txt`).
3. Run the provided Jupyter Notebook for EDA and modeling.

### Future Enhancements

- Incorporate external datasets (e.g., market indices, macroeconomic indicators).
- Build an interactive dashboard for real-time analysis.
- Improve predictive accuracy using advanced machine learning models.

### Contributors

- **Blex Olonde**  
  Data Science Enthusiast

---
