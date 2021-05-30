# Module 5:  PyBer with Matplotlib
---
## Overview of the Analysis
In this day and age, it is of utmost importance to be able to communicate information quickly and effectively to your audience.  In this module we were introduced to the Matplot library which is an excellent tool for creating professional, clean, and customizable visual representations of large data sets.  To practice with this library we worked with "Omar" to prepare a presentation for "V. isualize", the CEO of the fictional company PyBer. In this activity the CEO was interested in how the rideshare service was being used in different types of cities.  With this data the company hopes to allocate resources appropriately in the future to generate even more financial returns.  We prepared for our presentation by cleaning the data, merging the dataframes provided, creating new dataframes, and running basic statistics on the data.  Finally we used our analysis to create several graphs to display correlations between:
- type of city
- number of drivers
- number of uses
- average fare

---
## Results

After sifting through the data and creating the visualizations below we can conclude:
 - **there are more drivers in urban cities,** 
 - **the rideshare service is used the most frequently in urban cities,**
 - **the lowest average fare per ride is in urban cities,**
 - **the most total revenue comes from urban cities.**


![dataframe showing stats for each city](https://github.com/murphyk2021/PyBer_Analysis/blob/0f6fdd603b018431ca4824e8f2c99a96f36966cd/Analysis/summary_dataframe_edit.PNG)

In this bubble chart we can clearly see that in rural cities(yellow) there are fewer PyBer drivers available and the service is used less frequently.  However, each trip tends to be more expensive (likely from a longer traveling distance) than what we see in either suburban or urban cities. 
<p align="center">
  <img width="642" height="550" src="https://github.com/murphyk2021/PyBer_Analysis/blob/80ef60dd486d9a449f6cf51e4cb03c03c9e7167f/Analysis/Fig1.png">
</p>

Additionally, we can conclude that **there is fluctuation from week to week in the revenue gained in all types of cities** as shown in the line plot below.

![scatterplot showing total fare by week in the first quarter of the year](https://github.com/murphyk2021/PyBer_Analysis/blob/915418a24272a8ee0e825a2d99cdcb02fa891a62/Analysis/PyBer_fare_summary.png)

## Summary
These conclusions are not particularly surprising as populations residing in urban cities are less likely to own or regularly use individual vehicles.  Additionally, as urban cities have businesses and residencies in close proximity to each other geographically, residents would generally use the ride share service for shorter trips compared to those living in rural areas. From this data it may be concluded tht more resources should be allocated to the urban cities. 

However, to get even more robust data, it would be interesting to compare the population size and age, household income, and weather data to these different parameters.  For example:
 - What percentage of the total population uses the service?
 - Is there a correlation between usage and household income?
 - Is the service used more frequently during the week(for commuting) or on weekends(pleasure)?
 - Is there a correlation between weather and the total number of rides?
 - Which age range utilizes the service most frequently?
 
This additional information may help PyBer determine if the differences displayed in the data above is a result of user demand or PyBer supply and whether they need to focus more on marketing to particular groups of potential customers.

---

