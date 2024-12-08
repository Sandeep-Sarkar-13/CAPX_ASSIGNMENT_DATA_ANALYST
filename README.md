# CAPX_ASSIGNMENT_DATA_ANALYST
Stock Movement Analysis Based on Social Media Sentimen


Objective: Develop a machine learning model that predicts stock movements by
scraping data from social media platforms like Twitter, Reddit, or Telegram. The
model should extract insights from user-generated content, such as stock
discussions, predictions, or sentiment analysis, and accurately forecast stock price
trends.

Install Dependencies: Ensure you have Python installed along with the following libraries. You can install them using the command below:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib seaborn yfinance xgboost
Save the Code: Copy the provided code into a Python script file, such as stock_prediction.py.

Run the Script: Execute the script using your Python environment:

bash
Copy code
python stock_prediction.py
Modify Parameters: If you want to predict for a different stock, change the ticker variable in the script (e.g., 'AAPL' for Apple).

Review Outputs: The script will:

Fetch stock data from Yahoo Finance.
Process and engineer features.
Train an XGBoost model.
Print performance metrics (accuracy, precision, recall, F1-score).
Display a confusion matrix and feature importance plot.
Requirements
Python 3.7 or higher
Internet access (to download stock data from Yahoo Finance)
