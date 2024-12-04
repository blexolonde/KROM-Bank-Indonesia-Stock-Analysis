# **KROM Bank Indonesia Stock Historical Price Analysis**

## **Project Overview**  
This project analyzes the historical stock prices of KROM Bank Indonesia to uncover trends, patterns, and actionable insights. The analysis explores daily, weekly, and monthly stock data to support decision-making for investors, traders, and financial analysts.

---

## **Dataset Description**  

The project uses three datasets:  
1. **Daily Stock Prices (`BBSI.JK.csv`)**  
   - Historical daily stock prices with 1028 entries.  
   - Columns: `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`.

2. **Weekly Stock Prices (`BBSI.JK_weekly.csv`)**  
   - Weekly aggregated stock prices with 222 entries.  
   - Columns: Same as the daily dataset.  
   - Note: Some missing values.

3. **Monthly Stock Prices (`BBSI.JK_monthly.csv`)**  
   - Monthly aggregated stock prices with 51 entries.  
   - Columns: Same as the daily dataset.

---

## **Goals of the Analysis**  

1. **Explore Stock Trends**  
   - Analyze daily, weekly, and monthly stock trends.  
   - Visualize stock price movements and trading volumes over time.  

2. **Assess Risk and Performance**  
   - Calculate returns, volatility, and other key performance metrics.  
   - Perform risk analysis using historical price data.  

3. **Identify Patterns and Opportunities**  
   - Detect seasonality and significant patterns in stock performance.  
   - Highlight optimal buying and selling periods.  

4. **Predict Future Trends**  
   - Build predictive models using time-series data.  

---

## **Key Business Questions**  

1. How do stock prices and trading volumes vary over different timeframes?  
2. What is the historical volatility and risk-return profile of the stock?  
3. Are there specific times (e.g., months or weeks) that show consistent stock performance trends?  
4. Can historical data predict future stock prices or trends?  
5. How do adjusted closing prices differ from actual closing prices?

---

## **Steps to Reproduce the Analysis**  

1. **Dataset Preparation**  
   - Load the datasets into a Jupyter Notebook or Python environment.  
   - Perform data cleaning and handle missing values as needed.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize trends in `Open`, `High`, `Low`, `Close`, and `Volume`.  
   - Calculate performance metrics such as returns, volatility, and risk.

3. **Modeling and Forecasting**  
   - Apply time-series models like ARIMA or LSTM to predict future prices.  

4. **Visualization**  
   - Create plots for daily, weekly, and monthly trends.  
   - Compare patterns across different timeframes.

---

## **Technologies Used**  
- **Programming Language:** Python  
- **Libraries:** pandas, matplotlib, seaborn, statsmodels, scikit-learn  
- **Tools:** Jupyter Notebook  

---

## **How to Use the Code**  
1. Clone the repository.  
2. Install the necessary Python libraries (`requirements.txt`).  
3. Run the provided Jupyter Notebook for EDA and modeling.  

---

## **Future Enhancements**  
- Incorporate external datasets (e.g., market indices, macroeconomic indicators).  
- Build an interactive dashboard for real-time analysis.  
- Enhance predictive accuracy with advanced machine learning models.  

---

## **Contributors**  
- **Blex Olonde**  
  - Data Science Enthusiast  
   

--
