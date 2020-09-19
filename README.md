# Predicting the Stock Market

This repository contains a [notebook](https://github.com/jessedeans/Stock_Market_Prediction/blob/master/Stock%20Market%20Prediction.ipynb) and dataset used to predict the future price of the S&P 500 Index from historical data. The model is build on scikit-learn's linear regression model. The S&P 500 is a stock market index that aggregates the stock prices of 500 large companies, more information on the S&P 500 can be found [here](https://en.wikipedia.org/wiki/S%26P_500_Index). Predicting whether the index will go up or down helps forecast how the stock market as a whole will perform. 

**Note: You shouldn't make trades with any models developed in this notebook. Trading stocks has risks, and nothing in this notebook constitutes stock trading advice.**

## The Dataset

I'll be working with a csv file containing index prices. Each row in the file contains a daily record of the price of the S&P 500 Index from 1950 to 2015. The dataset is stored in `sphist.csv`.

I'll be using this dataset to develop the predictive model. I'll train the model with data from 1950-2012, and try to make predictions from 2013-2015.
