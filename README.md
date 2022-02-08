# Bitcoin

Objectives of this project: 

1) Does adding BTC to one's portfolio provide any diversification benefits?

I analyzed the correlation of bitcoin with S&P500, gold price, btc volume and USD_CAD exchanger rate. Year 2020 showed a significant jump in the correlation to the S&P500 index (0.38) and gold price (0.28). One could argue that the reason for the jump in correlation coefficients in 2020 is COVID-19, but the exact cause needs to be further investigated. It is interesting to note that though the correlation with gold and USD-CAD exchange rate has dropped in 2021, S&P500 index still appears to show significant correlation with bitcoin (0.30), a substantial jump from the year 2017 (0.02). Correlation with the SP500 is still inconsistent but if the upward trend continues, diversification benefits of having Bitcoin in the portfolio become questionable. 


![image](https://user-images.githubusercontent.com/45947172/152473644-3acd0745-b40b-411a-b145-75f3010ec807.png)

2) BTC price prediction using recurrent neural networks

Built a recurrent neural network model using LSTM to predict bitcoin price. 

This involded reshaping the time series data into a 2-dimension array so that the data can be used as inputs to the neural network model. Last 3 years (1095) of data was split into 80:20 split for train and test. Obtained an RMSE of 2237.7 on the test data

![image](https://user-images.githubusercontent.com/45947172/152473864-aad92474-275c-4cb5-812b-26374692e614.png)

Model's prediction for the next 10 days using the last 100 days of data: 

![image](https://user-images.githubusercontent.com/45947172/152474137-816774e5-0c15-49f2-9f5d-68a0966b0994.png)





