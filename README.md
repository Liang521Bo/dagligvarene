# dagligvarene
In this project, the store sales forecasting and store item demand forecasting will be included.

## Grocery Sales Forecast
A challenge facing the retail industry is to ensure the supply chain and warehouse space usage is optimized to ensure supply meets demand effectively, especially during spikes such as the holiday seasons. This is where accurate sales forecasting enable companies to make informed business decisions. Companies can base their forecasts on past sales data, industry-wide comparisons and economic trends. However, a forecasting challenge is the need to make decisions based on limited history. If Christmas comes but once a year, so does the chance to see how strategic decisions impacted the bottom line.

Historical sales data for stores located in different regions has been provided. Each store contains many departments, and the sales for each department in each store needs to be projected. Additionally, several promotional markdown events were performed throughout the year. These markdowns precede prominent holidays like Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. These markdowns are known to affect sales, but it is challenging to predict which departments are affected and the extent of the impact.

## Grocery Item Demand Forecast
Different time series techniques on a relatively simple and clean dataset were explored to predict grocery item demand.

5 years of store-item sales data are given, and 3 months of sales for 50 different items at 10 different stores is needed to predict .

The following questions were addressed. What's the best way to deal with seasonality? Should stores be modeled separately, or can you pool them together? Does deep learning work better than ARIMA? Can either beat xgboost?

The objective of the competition was to predict the sales of 10 different stores over 50 different items. The span of prediction were three months of 2018. In order to do this, 4 years of data (2013-2017) were provided.

The metric used to evaluate the results was the SMAPE:

 ![image](https://user-images.githubusercontent.com/53918424/123527051-89eb9900-d6dc-11eb-9ff7-246f757d24dc.png)

