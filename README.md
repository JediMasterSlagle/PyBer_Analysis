# PyBer Analysis

## Overview of Analysis

**PyBer** is a Python based ride-sharing app company, first assignment was to perform an exploratory analysis on data from large CSV files.
The analysis compares the relationships between the type of cities, number of drivers and riders, as well as percentages of total fares, drivers and riders based on the type of cities.  The goal for the initial analysis was to improve access and affordability for under served neighborhoods.<br>
The new analysis and visualization created below will help identify total weekly fares for each city type.

### Resources:

##### Data source:

[city_data.csv](https://github.com/JediMasterSlagle/PyBer_Analysis/blob/main/city_data.csv)
[ride_data.csv](https://github.com/JediMasterSlagle/PyBer_Analysis/blob/main/ride_data.csv)

##### Source code:  [PyBer_Challenge](https://github.com/JediMasterSlagle/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)
##### Software used: Python 3.7.9 64-bit (conda); jupyter-notebook


## Ride-sharing Results

In the initial analysis, once we merged the data from each CSV file and created a new PyBer dataframe, we were able to categorize all information by each city type; **Rural**, **Suburban**, **Urban**. data extracted:

  **1.**  Total rides by city type
  **2.**  Total drivers by city type
  **3.**  Total fares by city type
  **4.**  Average fares per driver
  **5.**  Average fares per ride

[PyBer_summary](https://github.com/JediMasterSlagle/PyBer_Analysis/blob/main/Fig8.png)


Based on PyBer summary we see

  - Urban cities are the most lucatrive,  There is more need in these areas and has the lowest fare per driver making trips quick and in larger amounts.
  - Suburban cities with 1000 less rides and roughly 2000 drivers less than the Urban cities, their average fare per driver is more than double caused by longer trip duration.
  - Rural cities have the lowest revenue, The average rate is about $10 higher than the urban cities and approximately $3 higher than the suburban cities.  Though when analyzing further the rural cities average fare per driver is $38.92 higher than the urban cities and $15.99 higher than the suburbs.  Based on the information there may not be enough drivers in the area nor the need for them as often.
  
  
Secondly we segregated and filtered the data further to get fares for January to end of April 2019 and calculated totals to get a sum of fares per week in the month.  
A multiple line chart was created with the results from the second analysis below are examples



[PyBer_fare_summary](https://github.com/JediMasterSlagle/PyBer_Analysis/blob/main/pyber%20summary.png)
[code_example](https://github.com/JediMasterSlagle/PyBer_Analysis/blob/main/weekly%20fare%20sum.png)

we can see there is no specific pattern except towards the end of February where all 3 city types have a spike in fare possibly due to number of rides occuring.


## Summary

My recommendations would be:

    a)  compare the fare rates between the types and possibly adjust to compensate for travel time,  gas etc for longer trips to check if the cost for a ride is consistant with the distance between the city types  
    b)  Calculating the average distance for each type of city and compare to see how distance effects fare cost or people possibly weighing the option of personal transportation,  public,  or ride share to determine what is best for them  
    c)  check if there is a need to increase the number of drivers in the rural area,  or to decrease the rate in suburban.  