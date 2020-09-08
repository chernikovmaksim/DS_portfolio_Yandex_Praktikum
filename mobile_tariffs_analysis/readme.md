# Аnalysis of mobile tariffs
## Project description
Customers are offered two tariff plans. In order to adjust the advertising budget, the commercial department wants to understand which tariff brings the most money. It is necessary to do a preliminary analysis of tariffs for a small sample of customers.
## Status
Done
## Goals
Determine the tariff that brings more money and make recommendations for the advertising department.
## Required libraries
pandas, numpy, scipy, matplotlib, seaborn
## Conclusion
Initial data processing was carried out from duplicates, missing and zero values. A flaw in the received data was revealed, and it is that data for some users were missing. Analysis of user actions by tariffs showed that, on average, users of each tariff began to call more often and for longer, send more messages and use the Internet more often. We managed to find out that the activity of users of the smart tariff is growing faster than that of users of the ultra tariff on average 2.3 times. In the course of the analysis, we managed to refute the hypothesis that the average revenue from the smart and ultra tariffs is equal, as well as confirm the hypothesis that the average revenue from Moscow and regional users is equal. As a result, we see that the ultra tariff brings on average more revenue than the smart tariff. However, the growth rate of user activity for the smart tariff is several times higher and the average revenue for the smart tariff is beginning to approach the average revenue for the ultra tariff. We also see that the activity of users on the ultra tariff is sagging in February for all indicators. In order to increase revenue and user activity, we propose to form a new advertising budget to attract new users on the ultra tariff, both new and among users of the smart tariff.
## Data
The following datasets were used:
* calls - information about calls
* internet - information about internet sessions
* messages - information about messages
* tariffs - information about tariffs
* users - information about users
