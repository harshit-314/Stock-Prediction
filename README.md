This model uses an LSTM Neural Netowrk to predict the price of any stock based on historical data.

The dataset for training was taken from yfinance.
The train:test split used was 80:20.
The model used data from the past 60 days to make a prediction.
After some basic preprocessing, the data was fed into a 4 layer LSTM network with 50 units each, followed by one dense layer.
The total training time for 30 epochs is around 8 minutes.

The results can be found in the pictures folder.


