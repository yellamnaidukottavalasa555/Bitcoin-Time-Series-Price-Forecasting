# Bitcoin-Time-Series-Price-Forecasting
Bitcoin is a decentralized cryptocurrency, which is a type of digital asset that provides the basis for peer-to-peer financial transactions based on blockchain technology. One of the main problems with decentralized cryptocurrencies is price volatility, which indicates the need for studying the underlying price model. Moreover, Bitcoin prices exhibit non-stationary behaviour, where the statistical distribution of data changes over time. This paper demonstrates high-performance deep learning models for predicting Bitcoin close price forecasting. Particularly, this study compares the accuracy of the prediction of bitcoin close price using different deep learning models: Convolution Neural Networks (CNN), Long-Short Term Memory (LSTM), Bidirectional Long-Short Term Memory (BiLSTM), Gated Recurrent Unit (GRU) and Bidirectional Gated Recurrent Unit (BiGRU). In this dissertation, the results do confirm that GRU predictions have better precision in terms of forecasting errors compared to the other models.

# Work Flow

## Dataset
The dataset provides the history of the daily prices of Bitcoin. The data starts from 17-Sep-2014 to 19-Feb-2022. The dataset contains Date, Open, High, Low, Close, Adj Close, and Volume columns. I suppose the price of bitcoin will keep growing in value. This is subject to proof after testing the data. So, the dataset contains 2713 rows by 7 columns. It contains information about the out-price dynamics of bitcoin against the USD that is, the opening and closing price of each day, the low and high price of each day as well as the volume traded on that day. This data was obtained from yahoo finance (https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD). However, this is real-time data that keeps updating. For example, if someone accesses it after some time, he/she will find that it has added on depending on the time of access. But the previous data will remain constant.

![image](https://user-images.githubusercontent.com/50575405/171634941-0b019ae8-9d5e-442f-bd72-a00613bc3fbe.png)



# Models
1. Convolutional Neural Networks
2. Long Short Term Memory
3. Bidirectional-Long Short Term Memory
4. Gated Recurrent Units
5. Bidirectional-Gated Recurrent Units

# Results
|          | RMSE     |    MSE      | MAE     | R2 Score | 
| :-------:| :-------:| :----------:| :------:| :-------:|
| CNN      | 5232.02  | 27374017.20 | 4387.37 | 0.88     |
| LSTM     | 8255.16  | 68147705.60 | 6988.87 | 0.72     |
| Bi-LSTM  | 6406.97  | 41049392.91 | 5199.89 | 0.83     |
| GRU      | 2604.54  | 6783632.43  | 1955.65 | 0.97     |
| Bi-GRU   | 2625.24  | 6891926.65  | 2017.39 | 0.96     |

# Conclusion
Machine learning techniques have recently gained a lot of popularity among the international community. The main purpose of this dissertation was to know whether these new approaches are more powerful than the traditional methods, or not. For this, I compared the accuracy of all the above-mentioned forecasts for a daily time series of bitcoin close prices.

The GRU predictions have better precision results in terms of forecasting errors are RMSE (2604.54), MSE (6783632.43), MAE (1955.65), and R2 Score (0.97), this model gives better forecasting error values when compared to the other models. We concluded that the GRU approach by large outperforms the other model outputs as previously mentioned.
