# dagligvarene
In this project, the store sales forecasting and store item demand forecasting will be included.

## Walmart Store Sales Forecast
Walmart is an American multinational retail corporation that operates a chain of hypermarkets, department stores and grocery stores. As of Jul 2019, Walmart has 11,200 stores in 27 countries with revenues more than $500 billion. A challenge facing the retail industry such as Walmart’s is to ensure the supply chain and warehouse space usage is optimized to ensure supply meets demand effectively, especially during spikes such as the holiday seasons. This is where accurate sales forecasting enable companies to make informed business decisions. Companies can base their forecasts on past sales data, industry-wide comparisons and economic trends. However, a forecasting challenge is the need to make decisions based on limited history. If Christmas comes but once a year, so does the chance to see how strategic decisions impacted the bottom line.

Historical sales data for 45 Walmart stores located in different regions has been provided. Each store contains many departments, and the sales for each department in each store needs to be projected. Additionally, Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. These markdowns are known to affect sales, but it is challenging to predict which departments are affected and the extent of the impact.

## Store Item Demand Forecasting Results
Quoting the Overview of the competition on Kaggle:

This competition is provided as a way to explore different time series techniques on a relatively simple and clean dataset.

You are given 5 years of store-item sales data, and asked to predict 3 months of sales for 50 different items at 10 different stores.

What's the best way to deal with seasonality? Should stores be modeled separately, or can you pool them together? Does deep learning work better than ARIMA? Can either beat xgboost?

This is a great competition to explore different models and improve your skills in forecasting.

The objective of the competition was to predict the sales of 10 different stores over 50 different items. The span of prediction were three months of 2018. In order to do this Kaggle provided us with 4 years of data (2013-2017).

The metric used to evaluate the results was the SMAPE:

SMAPE = \frac{100}{n} \sum_{t=1}^{n} \frac{\mid Y_t - Y_t \mid}{(\mid Y_t \mid - \mid Y_t \mid)/2}
