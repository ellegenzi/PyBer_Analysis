# PyBer: Ride Analysis

## Overview of Project

### Background and Purpose

I just landed a job as a data analyst for PyBer, a python-based ride-sharing app company. My first assignment was to perform an exploratory analysis on some of their data and create a variety of charts that showcase the relationships between the types of cities, the numbers of drivers and riders, and fare prices. After presenting this data, I was tasked with creating a summary DataFrame of the ride-sharing data by city type and creating a multi-line graph showing the total weekly fares for each city type. PyBer plans to use this analysis to improve access to ride-sharing services and determine affordability for under-served neighborhoods.

### Resources

- Data Source: city_data.csv, ride_data.csv
- Software: Anaconda 4.13, Matplotlib 3.5.1, Python 3.7.13, Visual Studio Code 1.68.1

## Results

### Summary DataFrame
Even though urban cities have the lowest average fares per ride and per driver, they have the highest amount of rides and drivers, bringing up the total fares for 2019 to nearly $40k, which is the highest for city types. Suburban cities have less than half of that with $19k for total fares and they are in the middle of the results in total rides and drivers, average fare per ride, and average fare per driver. Rural cities are the exact inverse of urban cities, with the highest average fares per ride and per driver, the lowest numbers of total rides and drivers, and the lowest total fares for the year at $4k. However, both suburban and rural cities have more total rides than drivers, while urban cities have more total drivers than rides. These results are all shown in Figure 1 below.

*Figure 1: Summary DataFrame of 2019 Ride-Sharing Results*

![SummaryDataFrame](https://user-images.githubusercontent.com/106830513/179646087-9cbce118-30e7-4ea4-b487-980bdd62f306.png)

### Multi-Line Plot

The multi-line plot showcases the weekly fares by city type for Jan 1 through April 28 for the year 2019. This plot echoes the results from the summary DataFrame in Figure 1 above in that urban cities consistently have the highest total fares per week, followed by suburban cities, and then rural cities with the lowest total fares. All three city types show a peak in weekly fares at the end of February and then there are various inconsistent peaks and valleys for each city type throughout. These results are all shown in Figure 2 below.

*Figure 2: Multi-Line Plot of Weekly Fares from Jan 1, 2019 through April 28, 2019*

![MultiLinePlot](https://user-images.githubusercontent.com/106830513/179646068-4b0271bb-262c-421f-ae18-099d70173bae.png)

## Summary

### Business Recommendations
Upon looking at the summary DataFrame and multi-line plot, one big conclusion can be drawn - urban cities bring in by far the most revenue. However, the amount of drivers is 1.5x the amount of rides for urban cities for the year, which means each driver isn't able to get a lot of business individually because they are fighting other drivers for rides. This may cause turnover with drivers unless the amount of rides increases. Alternately, in rural cities, there are 1.5x more rides than drivers, likely the leading cause of higher prices for customers, which may drive them away after one expensive experience.

These findings lead me to three business recommendations: (1) find more people who want rides in urban cities (and/or limit how many drivers there are in urban cities until the amount of rides increase), (2) get more drivers in suburban and rural cities, and (3) research a new pricing strategy that takes distance into account. I noted in the results of the multi-line plot above that across all city types, there seemed to be a general spike in rides at the end of February. I would suggest targeting a new marketing strategy to take effect for that time frame to capitalize upon the surge in rides. Subsequently, if the increase in rides isn't enough for urban cities to be in better balance with the amount of drivers, I would also incentivize some urban city drivers to move to suburban or rural cities to help those cities increase their driver counts. As far as a new pricing strategy, I believe it would help to provide a better balance of fare prices for drivers and customers across all city types. Rides in urban cities are likely the shortest in distance compared to suburban and rural cities and could benefit from a base price in addition to the normal fare to help drivers obtain a more equal pay for their time.
