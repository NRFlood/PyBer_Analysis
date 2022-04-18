# PyBer Analysis - Creating visuals with MatPlotLib

## Overview of PyBer Analysis

This assignment involved helping Omar scrub through the Pyber data and generate a new DataFrame in order to analyze the weekly fares of each different city type from January through April of 2019.  With this new DataFrame we were able to generate a multiple line graph that illustrates the performance of each city type for the leadership team at Pyber to use as they make strategic decisions.

## PyBer Analysis Results 

By using Pandas I was able to generate a new DataFrame that aggregated important ride-sharing information across the Urban, Suburban, and Rural city types in order to determine how they compare when it comes to the total number of rides, total drivers, total fares generated, average fare per ride, and average fare per driver. See code below:

![Summary_df](https://github.com/NRFlood/PyBer_Analysis/blob/main/analysis/Pyber_Summary_df_code.png)

Initial findings from this new DataFrame indicate that there is far more ride sharing available and taking place in Urban cities as compared to the other two markets.  Urban cities had *2.6x* as many rides as Suburban cities, and *13x* as many rides as Rural cities during the time period measured.  There were also nearly *5x* as many drivers in Urban cities as compared to Suburban cities, and *31x* as many drivers in Urban cities as compared to Rural cities.  This outcome is not much of surprise as more densely populate areas tend to have a greater demand for these types of services, thus creating more job opportunities for drivers, which leads to more rides being available.  As a result it is no surprise to see that the total Fares in Urban cities outpaces those generated in Suburban and Rural cities. The laws of supply and demand also appear to be holding true when comparing the average Fares across each city type, as the Urban cities tend to see lower average Fares due to the increase in competition amongst drivers.  One additional data point would be to look at the average distance of each ride to determine how much that contributes to the difference in Fares across cities.  

The new DataFrame also enabled me to create a multiple-line graph that measures the Fares collected by each city type from Jan-Apr of 2019. See graph below: 

![Graph](https://github.com/NRFlood/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

The graph also illustrates that the Urban cities in general generate more demand for ride sharing as compared to Suburban and Rural cities as evidenced by the gold line at the top of the graph, however the pattern of revenue in each city type tends to remain consistent throughout Jan and Feb with each city type hitting a peak in late Feb.  From that point on however the three city types start to deviate from one another with the Urban cities becoming more volatile in terms of revenue generation; the Suburban cities making a sharp decline and then remaining relatively flat until late April; and the Rural cities remaining relatively stable throughout March until reaching their highest point at the beginning of April, and then tapering back down again.

## PyBer Executive Summary

After comparing the results of the new DateFrame and multiple-line graph I would propose the following recommendations to CEO V. Isualize moving forward:

- Include average distance per ride to the data in order to better compare the average Fares per Ride and per Driver across each city type.  At first glance it appears there may be opportunity to add additional drivers to the Rural cities based on the revenue each ride generates, however if that increased revenue is the result of each ride being a longer distance then the data might not support adding services in those cities.
    
- Reduce the number of drivers in the Urban cities.  Currently there are nearly 1.5 drivers for every ride needed.  This would suggest that their own drivers are cannibalizing revenue from one another as they try to compete on price.  If there were fewer drivers they would likely be able to charge a higher fare per ride and still be able to meet the demand for the number of rides demanded.  This would increase revenue as each ride would now be serviced at a higher fare, and likely reduce overhead if there are fewer drivers being employed. 
    
- Consider running price promotions in the Suburban cities in late Feb.  This may help to smooth out the revenue stream if the demand for rides increases during that time period.  This may reduce the average Fares each driver is able to make per ride, but it might ultimately allow each driver to make more money by providing more rides, which in turn helps Pyber make more money as well.  
    
Naturally the overhead implications associated with making each of these strategic decisions needs to be considered as well, but these moves may help PyBer increase business going forward.
 
    
    



