# Stock-Prediction-Model
# Stock Price Prediction Using Sentiment Analysis from Reddit

This project aims to predict stock prices based on user sentiment analysis from Reddit posts. The sentiment is analyzed as Positive, Negative, or Neutral. Various machine learning models such as **Gradient Regressor**, **LSTM (Long Short-Term Memory)**, and **Random Forest** are used to predict future stock prices.

## Prerequisites

Before running the code, you need to install the required dependencies and set up your environment. The project is executed in a Jupyter Notebook environment.

# Install Jupyter Notebook

If you don't have Jupyter Notebook installed, you can install it via pip:pip install notebook

# Install Required Libraries
For Data Extraction from Reddit
To collect posts from Reddit regarding stock market price predictions, you need to install the following libraries:

PRAW: Python Reddit API Wrapper to extract data from Reddit.
JSON: To store the extracted data in JSON format.
yfinance: To get stock-related data.
re: To evaluate regex expressions.
Install these libraries using the following commands:


pip install praw
pip install json
pip install yfinance
pip install re

The collected data will be stored in a file named reddit_stock_data_final.json.

# Gradient Boosting Regressor
To use the Gradient Boosting Regressor model for predicting stock prices, install the following dependencies:


pip install pandas numpy scikit-learn matplotlib


# LSTM (Long Short-Term Memory) Model
For the LSTM model, install the following dependencies:

pip install pandas numpy tensorflow scikit-learn matplotlib

# Random Forest Regressor
For the Random Forest Regressor model, install the following dependencies:


pip install pandas numpy scikit-learn matplotlib

After installing all the required dependencies, open the stockmarket.ipynb Jupyter notebook.

Run the code blocks in the notebook sequentially.

When prompted:

Enter the stock symbol (e.g., AAPL, MSFT, etc.) for which you need the stock price prediction.
Enter the year for which you want the stock price to be predicted.
The program will output the predicted stock price for the entered stock symbol and year along with a graph comparing Actual vs Predicted stock prices.



