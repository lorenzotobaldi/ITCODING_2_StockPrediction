# ITCODING_2_StockPrediction
This project was initiated to investigate the use of autoregressive models in the stock market. Initially, we will consider the main metrics for analyzing price movement, such as moving averages and medians, both for lows and highs. 
In the second part of the code, we will create a fake portfolio with the selected stock and observe its performance while modifying the parameters (p, d, and q) of the default ARIMA model, which is set to (5,2,1) - the combination that yielded the best results in terms of total profit. The test will be conducted by splitting the data into two historical periods, one following the other, in an 80/20 ratio (train/test) relative to the total length.
