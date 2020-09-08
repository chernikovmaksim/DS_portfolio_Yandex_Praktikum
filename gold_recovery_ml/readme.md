# Gold recovery rate prediction
## Project description
Prepare a prototype machine learning model to predict the recovery rate of gold from a gold ore. The company develops solutions for the efficient operation of industrial enterprises.
## Status
Done
## Goals
A model needs to be developed that can predict the recovery rate of gold from gold ore.
## Required libraries
pandas, numpy, scikit learn, matplotlib, seaborn
## Conclusion
The data were analyzed and gaps in the characteristics were processed. The columns were converted to their respective data types and checked for duplicates. We were convinced of the correctness of the calculation of the enrichment efficiency, as well as the fact that the concentration of metals (Au, Ag, Pb) at different stages of purification changes in accordance with the technological process. After examining the total concentration of all substances at different stages, we found extreme values ​​that were removed from the training and test samples. As a result, the models were trained and the most accurate of them was chosen - "random forest in regression". This model was tested on a test set with an sMAPE score of 6.58.
## Data
The following datasets were used:
* data with mining and cleaning parameters
