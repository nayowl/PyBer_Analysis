# PyBer Analysis
## 1 Overview of The Project
Ridesharing is becoming one of the most popular methods for travelling. Rideshare companies enables people to match up with independent drivers at short time amount by using application. People can login into the application, enter the location and it will automatically shows the nearest available drivers.

PyBer is a ridesharing company that operates in urban, suburban and rural areas in U.S. This project will analyze PyBer ride data from January 2019 to April 2019 to help the company improve access to ride sharing services and determine affordability for underserved neighborhoods.

The following tasks will be performed in this analysis:
1.	Create a summary DataFrame contains of:

       a.	Total number of rides for each city type
  
       b.	Total number of drivers for each city type
  
       c.	Sum of the fares for each city type 
  
       d.	Average fare per ride for each city type
  
       e.	Average fare per driver for each city type
  
2.	Create a DataFrame for date range 2019-01-01 to 2019-04-28 that will shows the sum of the fares for each week and each city type.
3.	Create an annotated chart showing the total fares by city type. 


## 2 Resources

Data Source: city_data. csv , ride_data.csv

Software: Python 3.7.6 , Jupyter notebook, Pandas library, Matpotlib

## 3 Results 


<img width="413" alt="Summary Data Frame" src="https://user-images.githubusercontent.com/88597187/134695777-86600bdc-1d04-4968-86fb-3f0ddbc7560c.png">

<sub>Figure 1 Summary DataFrame for Each City Type</sub>

Figure 1 shows that the urban cities have the most amount for total rides and total drivers, which make the urban cities has the highest revenue compared to the other cities. On other hand, the average fare per ride and average fare per driver in urban cities is the lowest. This might indicate that the Pyber is a popular service in Urban cities as the total rides is the highest but the people in urban cities usually ride in shorter distance that makes the average fare is low. 

Suburban cities have the middle amount for all the field compared to rural and urban. Meanwhile, Rural cities had the lowest total rides, total rides and total fares. However, the average fare per ride and average fare per driver is the highest in the rural. This might indicate that PyBer is not that popular in rural cities, but people usually ride in longer distance compared to people in urban and suburban making the average fare is higher.

A multiple chart as shown in Figure 2 created to help visualize the total fares data in each city type from January 2019 to April 2019. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/88597187/134696061-610cdcb3-1eee-4509-a648-4c0013f7d2c4.png)
<p align="center">
<sub>Figure 2 Total Fare by City Type Chart</sub>
</p>
The urban cities have the highest total fare all through this time range, followed by suburban and rural. Total fare rose gradually for urban and suburban Cities from January and reached the peak in week 3 February. The graph is fluctuating for Urban cities from March to End of April while the total fares for suburban decreased until week 2 April and sharply increased until week 4 April.  The line graph for rural cities is quite stable overall with some increase in week 3 February and week 1 April.  In summary, urban, suburban, and rural cities have increased of total fares in week 3 February. 

## 4 Summary
Based on the summary data frame of ride data for each city type and total fare chart, below are three business recommendations for each city type:

•	Urban 

Pyber application is already quite popular in urban cities from what we can see in the total ride and total fares. To increase the revenue, Pyber can increase the fare on the peak time when the demand is high and nighttime when the public transport is not operating.  Another strategy is to add service like food delivery, pick up grocery or item delivery. 


•	Suburban

To increase revenue in suburban cities, PyBer can increase the number of driver when the demand is high in the specific weeks of months. From the graph, the demand is higher on week 3 February and end of April.  If its not possible, Pyber can increase the fares so the driver will get more money. 

•	Rural

We need more detailed data to understand why there are not many rides in rural areas. Whether it because of the low demand, or the lack number of drivers. The cause can be figured out by analyzing the comparison data on the ride fulfillments rate.

Based on the study, one of the biggest challenges with ridesharing in rural cities mainly because of the technological infrastructure. They depend on good cell service, while the rural broadband area usually unreliable making this can be one of the reasons why the demand is low. To overcome this, PyBer can make a call center for the rural areas so if there is no internet connection, people still can make a call to request driver. 

If the number of driver is too small, Pyber need to dig more why there are not many drivers join. They can make the reward more attractive so there will be many drivers want to join Pyber.



