# Taxi orders prediction
## Project description
To attract more taxi drivers during peak periods, you need to predict the number of taxi orders for the next hour.
## Status
Done
## Goals
It is necessary to build a model for predicting the number of taxi orders for the next hour. The RMSE metric value is not more than 48.
## Required libraries
pandas, numpy, scikit learn, lightgbm, statsmodels, matplotlib, seaborn
## Conclusions
The data were analyzed, resampling and decomposition of the time series were carried out. For prediction purposes, 4 variants of the models were trained, cross-validation was carried out and the best hyperparameters were obtained. As a result of fianal testing, the LGBMRegressor model showed the best RMSE 42.3 metric, which also predicts better than the previous value of the time series.
## Data
The following datasets were used:
* historical data on taxi orders at airports
