# Stock Prediction
This code performs stock prediction using a linear regression model in PySpark. It loads a dataset of stock prices, cleans the data, splits it into training and testing sets, engineers features, trains the model, evaluates its performance, and provides visualizations of historical stock prices, a heatmap of stocks, and a comparison of stocks from different companies.

# Prerequisites
Python 3.x
PySpark
Matplotlib
Seaborn
NumPy

# Dataset
The code expects a CSV file named all_stocks_5yr.csv containing the stock price data. Ensure that the file is located at the specified path: /Users/yassindinana/Desktop/Self-Learning/Stocks_Prediction/data/all_stocks_5yr.csv. Make sure the CSV file has the following columns in the specified order: "date", "open", "high", "low", "close", "volume", "Name".

# Setup and Execution
Install the required Python libraries: PySpark, Matplotlib, Seaborn, and NumPy.
Update the path to the dataset CSV file if necessary (/Users/yassindinana/Desktop/Self-Learning/Stocks_Prediction/data/all_stocks_5yr.csv).
Execute the code in a Python environment.

# Output
The code will output the Root Mean Squared Error (RMSE) of the model's predictions on the test data.

# Several visualizations will also be displayed:

Historical Stock Prices: A line plot showing the historical closing prices of stocks for different companies.
Heatmap of Stocks: A heatmap showing the correlation between the closing prices of different stocks over time.
Comparison of Stocks from Different Companies: A line plot comparing the historical closing prices of stocks from different companies.
Average of All Stocks: A line plot showing the average closing price of all stocks over time.
Predicted Stock Prices: A line plot showing the predicted closing prices of stocks based on the trained model.

# Closing
Once executed, the Spark session will be closed, and the program will terminate.

Please ensure that you have the necessary dependencies installed and the dataset file available before running the code.
