# Project 5: Stock Price Forecasting (ARIMA)

## 📌 Overview
In this project, I applied **Time Series Forecasting** techniques to predict Apple’s stock prices using historical data from 2015 to 2023. The goal was to build a model that can learn from past stock price patterns and forecast future values.

## 🛠️ Steps Followed
1. **Data Collection**  
   - Used the `yfinance` library to fetch Apple stock data (AAPL).  
   - Selected the **Close price** for analysis.  

2. **Exploratory Data Analysis**  
   - Plotted stock price trends from 2015–2023.  
   - Visualized the train-test split (80% train, 20% test).  

3. **Model Building (ARIMA)**  
   - Built an **ARIMA(5,1,0)** model using `statsmodels`.  
   - Trained it on the training dataset.  

4. **Forecasting**  
   - Forecasted stock prices for the test period.  
   - Compared forecasted values with actual stock prices.  

5. **Evaluation**  
   - Calculated error metrics:  
     - **MAE**: ~16.93  
     - **MSE**: ~424.52  
     - **RMSE**: ~20.60  
   - RMSE shows the model’s predictions are on average $20 away from actual prices.

## 📊 Results
- The ARIMA model successfully captured the stock price trend.  
- Forecast vs Actual comparison showed ARIMA could reasonably follow stock movement.  

## 💡 Skills Gained
- Time Series Analysis  
- ARIMA Modeling  
- Data Visualization (Matplotlib, Seaborn)  
- Model Evaluation Metrics  

## 📁 Files
- `Project5_Stock_Price_Forecasting.ipynb` → Full Jupyter/Colab notebook with code and analysis.  
- `README.md` → Project documentation.  

