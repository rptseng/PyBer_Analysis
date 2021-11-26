# PyBer_Analysis

## Overview
With ride-sharing data from 120 cities, categorized into Urban, Suburban, and Rural types, we will use Pandas DataFrames to summarize the amount of fares spent per ride on PyBer for each city type. We'll then employ Matplotlib to visualize the fares spent in each city type over the time horizon of January 2019 to April 2019.

## Results
### DataFrame by City Type
![pyber_summary_df](https://github.com/rptseng/PyBer_Analysis/blob/main/analysis/pyber_summary_df.PNG)

In this graphic, the data has been indexed by City Type, with counts of "Total Rides", "Total Drivers", and "Total Fares" for each. Calculations were created to display the "Average Fare per Ride" and "Average Fare per Driver" in each category as well.

Urban cities have the most "Total Rides", "Total Drivers" and "Total Fares", with Suburban cities and Rural cities rank second and third in each metric respectively.

We observe that the "Average Fare per Ride" at $34.62 and "Average Fare Per Driver" at $55.49 are the highest in Rural cities with Suburban and Urban cities ranking second and third in each metric respectively. We also observe that in Urban cities, the "Average Fare per Driver" at $16.57 is lower than the "Average Fare per Ride" at $24.53 due to having more drivers than rides.

### Line Chart of Total Fares by City Type
![pyber_fare_summary](https://github.com/rptseng/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

This line chart shows the Total Fares collected in PyBer rides from the period of January 1st, 2019 to April 29th, 2019. The data is resampled and plotted by week.
Urban cities collect the most fares, Suburban cities collect the second most fares, and Rural cities collect the lowest amount of fares through this period.

## Summary
Based on the results of processing the PyBer data, we can make the following three recommendations:
- Reduce the number of drivers in Urban cities - There are more drivers than rides in Urban cities, which means the supply of drivers exceeds the demand of rides taken in Urban locations and there may be an opportunity to maintain the same revenue while reducing cost of supporting 2,405 drivers.
- Reduce the fare rate in Rural cities - Rural cities feature the highest Average Fare Per Ride but the lowest Total Fares collected. There may be opportunity to increase the total number of rides taken by reducing the average fare of each ride, resulting in more Total Fares collected.
- Increase the number of drivers in Rural cities - There is a possibility that the number of rides taken in Rural areas are limited by the availability of drivers. Since Rural cities feature the highest Average Fare Per Driver than Urban and Suburban cities, adding more drivers to these locations may be an opportunity to expand revenue.