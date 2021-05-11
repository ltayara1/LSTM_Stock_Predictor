# Long Short Term Memory (LSTM) Stock Predictor

## Background
Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. 

I built and evaluated deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data. I used deep learning recurrent neural networks to model bitcoin closing prices. One model uses the FNG indicators to predict the closing price while the second model uses a window of closing prices to predict the nth closing price. To make this happen, I took the following steps:

 - Prepare the data for training and testing
 - Build and train custom LSTM RNNs
 - Evaluate the performance of each model
 
## Evaluate the performance of each model

#### Which model has a lower loss?
The model using closing prices has a lower loss.

#### Which model tracks the actual values better over time?
The model using closing prices tracks the actual values better over time.


#### Which window size works best for the model?
The smaller the window, the better the fit. 