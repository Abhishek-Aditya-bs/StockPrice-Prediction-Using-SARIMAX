# StockPrice-Prediction-Using-SARIMAX
Predicting Future Stock Price Values using Time Series Analysis and Models like ARIMAX and SARIMAX. 

Stock market prediction is defined as “the act of trying to determine the future value of a company stock or other financial instrument traded on an exchange”. Predicting future values of stock prices can yield great profits for the company. However, the task is not particularly an easy one as it can involve numerous factors (both physical and psychological), making share prices particularly volatile. Investment banks are institutions that act in an advisory role to help companies, individuals or governments make financial transactions.

Major shareholders of the media conglomerate, Waystar Royco (WAYA US) have hired the investment bank you work at, as consultants to analyse their performance in the stock market and make future predictions. Your team, as business analysts in the investment bank, has to predict the closing stock price of the company from 30th July, 2021 to 10th September, 2021 as accurately as possible, given data from 14th August, 2015 to 29th July, 2021. The data you have been provided with, consists of the opening, high, low and closing price of Waystar Royco’s stock as well as the volume of stocks traded in a day, for 1500 days. Your team has been instructed to use ONLY this information and disregard any other factors while making predictions. In addition to this, the bank also wants to know what models are best suited for stock price predictions given similar data and wants your team to perform a comparison between regression and time series models so that they know what to adopt for future scenarios.

DISCLAIMER: Waystar Royco is a fictional company, so any information apart from what is given in the description above, is irrelevant to the problem statement at hand.

# Dataset
The main dataset (train.csv) consists of stock prices of Waystar Royco from 14th August 2015 to 29th July 2021. These include the opening, low, high and closing prices on a particular day, as well as the volume of stocks traded in that day. The target attribute is the closing price. Please note that you will have to decide on train-test split yourselves and provide the rationale behind your decision.

## Attributes
1. Date: datetime, ID, consists only of weekdays
2. Open: double, the price at the time trading begins in the stock market
3. High: double, the highest price during trading hours of the stock market
4. Low: double, the lowest price during trading hours of the stock market
5. Volume: integer, the volume of stocks traded on that day
6. Close: double, the price at the time trading closes in the stock market

# Files
1. `train.csv` : Main dataset
2. `test.csv` : Data for which close price needs to be predicted

#   Functionalities Implemented

1. Analysis of the dataset provided
2. Model using regression and time series techniques
3. Providing comparative analysis based on performance metrics and technical domain knowledge using documentation and graphs.
4. Predict closing stock prices from 30/07/2021 to 10/09/2021 
5. Metric used for evalauation is RMSE 
