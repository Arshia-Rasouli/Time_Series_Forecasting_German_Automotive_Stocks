# Time Series Forecasting of Automotive Stocks

This project focuses on **time series forecasting** of stock prices for three major automotive firms — **Volkswagen (VW)**, **Porche**, and **BMW**.  
The goal is to explore how well different statistical models can capture the underlying market patterns and predict future price movements.

##  Project Overview

The analysis is divided into three main stages:

1. **Data Preparation**  
   Cleaning, transforming, and organizing the time series data for each company.

2. **Modeling and Forecasting**  
   Applying and comparing forecasting models (auto_arima) to evaluate predictive performance and accuracy.

3. **Volatility Analysis (VW)**  
   For Volkswagen, an additional **GARCH(1,1)** model was estimated to analyze how volatility behaved **before and after** a detected structural change (`ann_1`).

##  Key Insights

- Time series models were able to effectively capture the general trends and short-term dynamics of stock movements.  
- Forecast accuracy varied between companies, highlighting different market behaviors.  

##  Tools

- Python 
- Statsmodels
- Auto_ARIMA   
- Pandas, NumPy  
- Arch (for GARCH modeling)  
- Matplotlib

##  Results and Discussion

The project provides a practical comparison of forecasting methods in a real-world financial context.  
Additionally, the volatility modeling for VW adds a deeper understanding of how **market stability** can shift across different time periods.


