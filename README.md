# Bitcoin-Time-Series-Price-Forecasting
Bitcoin is a decentralized cryptocurrency, which is a type of digital asset that provides the basis for peer-to-peer financial transactions based on blockchain technology. One of the main problems with decentralized cryptocurrencies is price volatility, which indicates the need for studying the underlying price model. Moreover, Bitcoin prices exhibit non-stationary behaviour, where the statistical distribution of data changes over time. This paper demonstrates high-performance deep learning models for predicting Bitcoin close price forecasting. Particularly, this study compares the accuracy of the prediction of bitcoin close price using different deep learning models: Convolution Neural Networks (CNN), Long-Short Term Memory (LSTM), Bidirectional Long-Short Term Memory (BiLSTM), Gated Recurrent Unit (GRU) and Bidirectional Gated Recurrent Unit (BiGRU). In this dissertation, the results do confirm that GRU predictions have better precision in terms of forecasting errors compared to the other models.

# Work Flow

## Dataset
The dataset provides the history of the daily prices of Bitcoin. The data starts from 17-Sep-2014 to 19-Feb-2022. The dataset contains Date, Open, High, Low, Close, Adj Close, and Volume columns. I suppose the price of bitcoin will keep growing in value. This is subject to proof after testing the data. So, the dataset contains 2713 rows by 7 columns. It contains information about the out-price dynamics of bitcoin against the USD that is, the opening and closing price of each day, the low and high price of each day as well as the volume traded on that day. This data was obtained from yahoo finance (https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD). However, this is real-time data that keeps updating. For example, if someone accesses it after some time, he/she will find that it has added on depending on the time of access. But the previous data will remain constant.

![image](https://user-images.githubusercontent.com/50575405/171634941-0b019ae8-9d5e-442f-bd72-a00613bc3fbe.png)



# Models
