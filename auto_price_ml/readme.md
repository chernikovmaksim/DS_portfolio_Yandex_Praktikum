# Auto price prediction
## Project description
Used car sales service is developing an application to attract new customers. In it, you can quickly find out the market value of your car. <br>
Important for the customer:<br>
* quality of prediction
* prediction speed
*	studying time
## Status
Done
## Goals
Its need to develop a fast machine learning model that will help you find out the market value of your car.
## Required libraries
pandas, numpy, scikit learn, lightgbm, catboost, matplotlib, seaborn
## Conclusions
The data was analyzed, gaps, zero values in characteristics and duplicates were processed. Categorical features were coded, quantitative ones were scaled. For the purpose of predicting the price of cars, 2 models CatBoostRegressor and LGBMRegressor were used, which showed excellent results in comparison with the constant model. As a result of studying the learning rate and selection of hyperparameters, the LGBMRegressor model won, which, other things being equal, selects hyperparameters 2 times faster. 
## Data
The following datasets were used:
* data with technical characteristics, configuration and prices of cars
