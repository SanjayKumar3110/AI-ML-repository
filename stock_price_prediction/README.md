# Stock Price Prediction using Linear Regression

## Overview
This project uses **Linear Regression** to predict stock prices based on historical data. The goal is to understand how machine learning can be used for financial forecasting.

## Dataset
- **Source:** Yahoo Finance  
- **Features Used:** Open, High, Low, Close, Volume  
- **Target Variable:** Next-day closing price  

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

## Steps in the Project
1. **Data Collection** – Fetched stock data using `yfinance` API.  
2. **Data Preprocessing** – Converted dates, normalized prices, and added moving averages.  
3. **Model Training** – Used `LinearRegression` from `scikit-learn` to predict stock prices.  
4. **Evaluation** – Measured accuracy using Mean Squared Error (MSE) and R² score.  
5. **Model Saving** – The trained model is saved as `stock_price_model.pkl`.  

## How to Run the Project
1. Clone this repository:
2. Install the required libraries:
3. Open and run `Linear_Regression.ipynb` in Jupyter Notebook.  
4. Load the saved model to make new predictions:
