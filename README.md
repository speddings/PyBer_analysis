# PyBer_analysis
## Overview of PyBer Analysis

The purpose of this anlysis is to improve access to ride sharing services and determine affordability for underserved neighborhoods. The CEO has asked for a summary DataFrame of the ride-sharing data by city type, with a multiple-line graph that shows the total weekly fares for each city type. 

## Resources
- Data Source: city_data.csv, PyBer_ride_data.csv
- Software: Python v 3.7, Anaconda, Jupyter Notebook
  
## PyBer Analysis Results

The following key metrics were calculated and a dataframe was created to analyze key performance indicators in the city types.

![dataframe](/analysis/df_summary.png)

### DataFrame Analysis

1. Urban cities generate the most revenue for PyBer
2. Customers in Urban cities pay less per ride and therefore drivers earn less per ride
3. Urban cities have more total drivers than total rides. 
4. Even though rural cities have less total rides, drivers make 3 times more per ride than urban cities.

View additional charts on city types by [total fares](analysis/Fig5.png), [total rides](analysis/Fig6.png), and [total drivers](analysis/Fig7.png).

Per the CEO's request, a multiple line chart was created as part of the analysis to help visualize and analyze the total fares from January to April 2019 for each of the city types.

![summary](/analysis/PyBer_fare_summary.png)

### Line Chart Analysis
1. Urban city types had the highest total fares for all the weeks and rural areas had the least. 
2. Total fares peak the 3rd week of February  for each city type. 
3. Urban cities aslo show increases in revenue in the first and third week of March. 


## PyBer Analysis Summary

The analysis leads to three business recommendations to address disparities among the city types. 

- __Reduce number of urban city drivers.__ Urban cities have more total drivers than total rides. There are 2,405 drivers which made only 1,625 rides. This means 33% of drivers made zero rides. Both suburban and rural city types show the reverse - more total rides than total drivers. Reducing number of drivers will increase average fare per driver for the urban city type.
- __Increase nummber of rural city type drivers.__ Rural cities return the lowest total rides and lowest total drivers among all three city types, however rural city types show the highest returns for average fare per driver and average fare per ride. Therefore, increasing number of drivers in rural cities , even just a little, would increase PyBer reveune.
- __Analyze ride duration (or ride distance).__ It might be interesting to determine and analyze other factors that are contributing to the high ride costs in rural cities and low ride costs urban cities such as ride duration. Are rural rides longer in distance and therefore more expensive? 
