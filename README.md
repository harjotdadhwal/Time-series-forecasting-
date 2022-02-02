## Time Series Forecasting using a hybrid Deep learning and Random Forest model

### Contents and problem statement definition 
This repository contains a sample of time series forecasting for a high frequency-short interval period data. Here, task at hand is to forecast electricity prices in a deregulated & a highly volatile market. This is a classic case of high variance in the data(as electricity prices are highly volatile) where traditional time series forecasting techniques fail to perform. 

### ML system flow
This repository has the final model pipeline and doesn't cover insights from the initial data collection, data wrangling, imputations, data aggregation using clustering, EDA, hypothesis testing and feature engineering. It contains the following:
- Data structuring 
- Creating the hybrid model 
- Electricity price spike classification using Autoencoder
- Estimating electricity prices using Random Forest regressor
- Model validation  

### Backround 
The electricity market in Alberta,Canada is deregulated, meaning one can purchase electrical energy from a wide range of private retailers. Energy is sold by generators at prices set by the given demand in Alberta. This makes the prices highly volatile and unpredictable. A better visibility on future electrcity prices can reduce dependencies on existing generators and aid in self generation or help take intelligent energy decisions. 
