# Stock Price Prediction with LSTM Neural Network

## Overview

This project implements a stock price prediction model using a Long-Short-Term Memory (LSTM) Neural Network. The model is built using the Keras and Scikit-learn modules, and the results are visualized using Jupyter Notebook and Matplotlib. The primary focus is on predicting the closing price of AAPL Inc. based on the past 60 days' stock prices.

## Prerequisites

Before running the code, ensure you have the following libraries installed:

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Keras
- Matplotlib
- yfinance
- pandas_datareader

You can install these dependencies using the following command:

```bash
pip install pandas numpy scikit-learn keras matplotlib yfinance pandas_datareader
```

## Getting Started

```bash
git clone https://github.com/your-username/stock-price-prediction.git
cd stock-price-prediction
```
1. Open the Jupyter Notebook file Stock_Price_Prediction.ipynb using Jupyter Notebook.
2. Run the notebook cell by cell to execute the code and visualize the results.

## Code Structure
- The code begins by importing necessary libraries and setting up the environment.
- Stock data is obtained using the Yahoo Finance API for AAPL Inc. within the specified date range.
- Data visualization is performed to understand the closing price history.
- Data preprocessing involves scaling the data and creating training and testing datasets.
- The LSTM model is constructed using Keras, compiled with the Adam optimizer, and trained on the training dataset.
- Testing data is used to make predictions, and the root mean squared error (RMSE) is calculated for model evaluation.
- Finally, the results are visualized, comparing the actual closing prices with the predicted values.

# Results
The LSTM Neural Network demonstrates its predictive capabilities with high accuracy, as shown in the visualizations within the notebook. The RMSE provides insight into the model's performance, and users can further tweak hyperparameters for optimization.

Feel free to experiment and enhance the model for more accurate predictions or apply it to different stock datasets. Happy coding!
