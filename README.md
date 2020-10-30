# PyBer Analysis

## Overview of Project
The purpose of this analysis is to provide insight on PyBer ride trends in urban, suburban and rural cities. Date, fare and geographic information was collected from 2,375 rides in 120 cities from January to May 2019. This report draws on analysis on rides from January to April 2019 to make recommendations on addressing disparities among city types. 

## Results
**Summary of Data**
![Summary](/analysis/SummaryDF.jpg)
The table above shows the data disaggregated by city type: Rural, Suburban, and Urban. While the average fare per ride ranges from $24.53 to $34.62, differing by $10, the average fare per driver is $16.57 for urban cities and $55.49 in rural cities, a difference of almost $39. If driver payment structure is reflective of the average fare per driver, this illustrates an inequality in driver pay in different city types. The following calculation was used to find the average number of rides per driver within the five month period. 

![avg_rides_per_driver](/analysis/avg_rides_per_driver.jpg)

This calculation finds that, on average, drivers in rural cities receive about one more ride than their urban counterparts. Using the calculated average rides per driver and average fare per driver (see the calculation below), further analysis of the data finds that drivers in rural cities made $77 more than their urban peers during the time period.  

![total_fares_per_driver](/analysis/total_fares_per_driver.jpg)

The disparity between rural and urban drivers could be due to the number of in-service drivers in the cities. The rural average fare per drive is almost four times the rural average. The following calculation was used to find the average number of drivers per city per city type.

![avg_drivers](/analysis/calculate_driver_avg.jpg) 
On average, there are nines times more drivers available in urban cities than there are in rural cities. Following supply-demand economics, this analysis assumes that as the number of drivers in cities increase, the fare cost decreases.  

![line_chart](/analysis/Pyber_Fare_Summary.png)
The chart above summarizes weekly fare totals for rural, suburban, and urban cities from January 2019 to April 2019. As with fare averages discussed previously, rural city totals fall way below the totals for urban and suburban cities. Despite the large disparity in fare totals, all types show a sharp increase at the end of February and then decreases at the start of March. 
