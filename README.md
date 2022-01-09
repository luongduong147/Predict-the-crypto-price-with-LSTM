# Predict-the-crypto-price-with-LSTM
A sample of LSTM architecture to predict the AAVE prices. Data: https://www.kaggle.com/tusharsarkar/cryptodatapart1. Many of Deep Learning architechture used to predict/forecast the price time series data and RNN is a pretty good model. LSTM can eliminate some defects of RNN as vanishing gradient, long-term dependency...
A trading strategy you can try :
Buy when the predict price at t+1,t+2,t+3 higher than the close price at moment t 
Sell when the predict price at t+1,t+2,t+3 lower than the close price at moment t 
Stop loss base on ATR/Stdev
The idea of trading strategy given by : http://dspace.unive.it/bitstream/handle/10579/12450/842777-1212885.pdf?sequence=2
Backtest them and forward test at least 3 months
