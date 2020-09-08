# Oil production
## Project description
You have been provided with oil samples in three regions: in each - 100,000 fields, where the quality of oil and the volume of its reserves were measured. You need to decide where to drill the new well.
## Status
Done
## Goals
It is necessary to build a machine learning model that will help determine the region where oil production will bring the greatest profit. It is also necessary to analyze the possible profit and risks using the Bootstrap technique.
## Required libraries
pandas, numpy, scikit learn
## Conclusion
The incoming data has been analyzed. Redundant signs (well id column) were removed. To solve the problem, there was a linear regression model. For the 3 analyzed regions, models were trained to predict the resources that can be produced from the wells. Also, the budget and expenses were analyzed and the break-even point was determined in the volume of raw materials of 2,222.22 thousand bar. To find the distribution of profit, the Bootstrap technique with 1000 samples was applied. As a result, the 2nd region was identified as the most profitable and risky. This region with a high degree of probability will bring from 90 to 100 billion rubles. with a budget of 10 billion. It will be proposed to management for the development of new fields.
## Data
Geological prospecting data for three regions
