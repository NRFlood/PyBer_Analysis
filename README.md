# PyBer Analysis - Creating visuals with MatPlotLib

## Overview of Pyber Analysis

This assigment involved helping Omar scrub through the Pyber data and generate a new DataFrame in order to analyze the weekly fares of each different city type from January through April of 2019.  With this new DataFrame we were able to generate a multiple line graph that illustrates the performance of each city type for the leadership team at Pyber to use as they make strategic decisions.

## Pyber Analysis Results 

By using Pandas I was able to generate a new DataFrame that aggregated important ride-sharing information across the Urban, Suburban, and Rural city types in order to determine how they compare when it comes to the total number of rides, total drivers, total fares generated, average fare per ride, and average fare per driver. See code below:

![Summary_df](https://github.com/NRFlood/PyBer_Analysis/blob/main/analysis/Pyber_Summary_df_code.png)

Initial findings from this new DataFrame indicate that their is far more ride sharing available and taking place in Urban cities as compared to the other two markets.  Urban cities had *2.6x* as many rides as Suburban cities, and *13x* as many rides as Rural cities during the time period measured.  There were also nearly *5x* as many drivers in Urban cities as compared to Suburban cities, and *31x* as many drivers in Urban cities as compared to Rural cities.  This outcome is not much of surprise as more densly polpulate areas tend to have a greater demand for these types of services, thus creating more job opportunities for drivers, which leads to more rides being avalailable.  As a result it is no surprise to see that the total Fares in Urban cities outpaces those generated in Suburban and Rural cities. The laws of supply and demand also appear to be holding true when comparing the average Fares across each city type, as the Urban cities tend to see lower average Fares due to the increase in competition amoongst drivers.  One additional data point would be to look at the average distance of each ride to determine how much that contributees to the difference in Fares across cities.  

The new DataFrame also enabled me to create a multiple-line graph that measures the Fares collected by each city type from Jan-Apr of 2019. See graph below: 

![Graph](https://github.com/NRFlood/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)



