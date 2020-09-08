# Game industry analysis
## Project description
Analyze the gaming industry and identify patterns that determine the success of the game to bet on a potentially popular product and plan ad campaigns
## Status
Done
## Goals
Аnalyze platforms, genres, ratings and identify user portraits of each region. Test hypotheses on platform and genre ratings.
## Required libraries
pandas, numpy, scipy, matplotlib, seaborn
## Conclusion
Initial data processing was carried out from duplicates, missing and zero values. A defect in the received data was revealed, and it is that ratings for some games were absent or were in the "tbd" status. We analyzed the processed data. We found out that sales of games were growing until 2008 and with the onset of the crisis began to decline. We managed to identify the average lifespan of the platform, which is 10 years. The most promising platforms at the end of 2016 are PS4 and Xbox One. Each platform has emissions, which represent a hit game that sells many times more than the rest of the games on the platform. There is an average positive correlation between critical ratings and sales. User ratings have little to no correlation with sales. The most profitable genres of the last 5 years are: action, shooter and RPG. After analyzing the data obtained, we have compiled a portrait of the most typical user for each region. Users in Japan and Europe / North America vary greatly in both platform preference and preferred genres. Our analysis confirmed the hypothesis that the average user ratings for the Xbox One and PC platforms are the same, and that the average user ratings for the Action and Sports genres are different.
## Data
The following datasets were used:
* historical game sales data, user and expert ratings, genres, and platforms (e.g. Xbox or PlayStation)
