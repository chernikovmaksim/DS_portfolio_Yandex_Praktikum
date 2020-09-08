# Bank customer churn prediction
## Project description
Clients began to leave the bank. It is necessary to predict whether the client will leave the bank in the near future or not. 
## Status
Done
## Goals
It is necessary to develop a machine learning model that predicts the churn of bank customers. To deliver the project successfully, need to bring the F1 metric to 0.59.
## Required libraries
pandas, numpy, scikit learn, matplotlib, seaborn
## Conclusion
The incoming data has been analyzed. Redundant signs and objects with gaps were removed, categorical signs were coded, and quantitative ones were scaled. To solve the classification problem, 2 models were chosen: random forest and logistic regression. The best hyperparameters were selected for these models. Various methods were applied to combat class imbalance, and as a result, the one that showed the best F1 metric on the corresponding model was chosen. The chosen model of a random forest shows a high accuracy - 85.39%, the level of class prediction is above average and amounted to F1 = 0.6076, which is more than 0.59 from the problem statement. The ROC curve demonstrates a good quality of the model (the proportion of truly positive responses is greater than the proportion of false positives). The area under the ROC-curve was 0.84, which is a good indicator.
## Data
The following dataset were used:
Source: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling
