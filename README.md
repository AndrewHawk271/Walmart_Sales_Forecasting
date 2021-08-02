# Walmart_Sales_Forecasting
The repository contains code to solve this Kaggle competition: https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/overview

Since I am running this script on my laptop, computing resources are an issue. Thus, my current model only predicts the next 20 days of sales for department 3 of all stores.  
I use a simple SARIMA model (the next step is to incorporate exogenous variables i.e. SARIMAX).    
Below are the WMAEs of my model and a model of all zeros (which is used as a benchmark in the Kaggle competition):    
WMAE = 3621  
WMAE all zeros = 17460.56 (benchmark)
