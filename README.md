# PyBer_Analysis

## Project Overview

Analysis of PyBer's ride-sharing data to understand how data differs by city type. Visualize findings and provide recommendations.

## Resources

- Data Sources: city_data.csv, ride_data.csv
- Software: Python 3.9, Anaconda3 2021.05, Jupyter Notebook 6.3.0

## PyBer Analysis Results

A summary comparison of rides originating from rural, suburban, & urban city types can be found in the table below:

![](/analysis/Challenge_comparison_table.png)

#### Total Rides

Urban city tpe rides make up the largest percentage of total rides by a large margin (68.4%). Suburban city type rides make up about 26% of total rides, and the remaining 5.3% of total rides are from rural city types. 

![](/analysis/Fig6.png)

#### Total Drivers

Urban city type drivers make up an even larger percentage of total drivers (80.9%).  Suburban city type drivers make up 16.5% of total drivers, and the remaining 2.6% of total drivers are from rural city types.

![](/analysis/Fig7.png)

#### Average Fare Per Rider & Driver

* Urban city type rides have an average fare per rider of $24.53 and an average fare per driver of $16.57.
* Suburban city type rides have an average fare per rider of $30.97 per ride and an average fare per driver of $39.50.
* Rural city type rides have an average fare of $34.62 per rider and an average fare per driver of $55.49.

To better understand the data behind the average fares per rider by city type, the box & whisker plot summarizes the distribution:

![](/analysis/Challenge_Fares.png)

#### Total Weekly Fare by City Type

Throughout the year, urban city type rides receive the most fare each week, followed by suburban and then rural city types.  

![](/analysis/Challenge_fare_summary.png)

## Summary
Based on the results above, we can make the following recommendaitons:
 1. Incentivize drivers in urban areas to book/accept more rides from suburban areas. 
 2. Incentivize drivers from both urban & suburban areas to book/accept more rides from rural areas, as they have the highest average fare per driver.
 3. Focus on adding drivers and riders in rural areas in an effort to reduce the variance of ride fares. 
