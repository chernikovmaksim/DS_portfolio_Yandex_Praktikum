# Steel temperature prediction
## Project description
To optimize production costs, the smelter decided to reduce energy consumption during the steel processing stage.
## Status
Done
## Goals
It is necessary to build a model that predicts the temperature of the steel in order to optimize production costs.
## Required libraries
pandas, numpy, scikit learn, lightgbm, matplotlib, seaborn
## Conclusion
The data were analyzed and combined, outliers and omissions processed. Quantitative traits have been scaled up. For the purposes of temperature prediction, 3 models LinearRegression, RandomForestRegressor and LGBMRegressor were used, which showed excellent results compared to the naive model. As a result of evaluating the MAE metric and selecting hyperparameters, the LGBMRegressor model won, the final testing of which showed an MAE at 6.02. We also managed to identify the features that most affect the model: Full Power (full power for all iterations) and Temp first (first temperature measurement in the batch), which looks logical. It turns out that I control the initial temperature and heating power at each iteration, we can control energy costs and effectively distribute them for each batch. For further analysis, it will be necessary to observe the indicators and identify deviations from the average values and fix the reasons: composition of gas, steel, initial temperature, etc. Having fixed the reasons, it will be possible to develop energy saving measures.
## Data
The following datasets were used:
* data on electrodes
* data on the supply of bulk materials (volume)
* data on the supply of bulk materials (time)
* data on gas blowing of the alloy
* temperature measurement results
* data on wire materials (volume)
* wire material data (time)
