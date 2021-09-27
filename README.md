# PyBer Analysis
## 1 Overview of The Project
Ridesharing is becoming one of the most popular methods for travelling. This type of service enables people to match up with independent drivers in a short amount of time by using application. User can login into the application, enter the location and it will automatically shows the nearest available drivers.

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

Figure 1 shows that the urban cities have the most amount for total rides and total drivers, which showcases the urban cities generate the highest revenue compared to the other cities. On other hand, the average fare per ride and average fare per driver in urban cities is the lowest. This might indicate that the Pyber is a popular service in Urban cities as the total rides is the highest but the people in urban cities usually ride in shorter distance that makes the average fare is lower. 

Suburban cities have the middle amount of all the field compared to rural and urban. Meanwhile, Rural cities have the lowest total rides and total fares. However, the rural areas generate the highest average fare per ride and the average fare per driver. This might indicate that PyBer is not that popular in rural cities, but users usually ride in a longer distance compared to the ones in urban and suburban.

A multiple chart as shown in Figure 2 created to help visualize the total fares data in each city type from January 2019 to April 2019. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/88597187/134696061-610cdcb3-1eee-4509-a648-4c0013f7d2c4.png)
<p align="center">
<sub>Figure 2 Total Fare by City Type Chart</sub>
</p>
The urban cities have the highest total fare all through this time range, followed by suburban and rural. Total fare rose gradually for urban and suburban Cities from January and reached the peak in 3rd week of February. The graph is fluctuating for Urban cities from March to end of April while the total fares for suburban decreased until 2nd week of  April and sharply increased until 4th week of April.  Overall, the line graph for rural cities is quite stable  with some increment in 3rd week of  February and 1st week of  April.  In summary, urban, suburban, and rural cities generate  total fares increment in 3rd week of February. 

## 4 Summary

The following are three business recommendations for each city typeB based on the summary data frame of ride data for each city type and total fare chart:

•	Urban 

Pyber application is already quite popular in urban cities based on  the total ride and total fares. To increase the revenue, Pyber can raise the fare on the peak time when the demand is high and nighttime when the public transport is not operating.  Another strategy is to expand the service such as food delivery, grocery pick up or item delivery. 


•	Suburban

To increase revenue in suburban cities, PyBer can increase the number of driver when the demand is high in the specific weeks of the months. Based on the graph, the demand is higher on 3rd week of February and end of April.  If it is not possible, Pyber can increase the fares hence the driver will get more income. 

•	Rural

More detailed data is required to learn about the cause of ride shortages in rural area. Whether it is caused  by the low demand, or the lack of drivers. The cause can be figured out by analyzing the comparison data on the ride fulfillments rate.

Based on the study, one of the biggest challenges with ridesharing in rural cities mainly because of the technological infrastructure availability. They depend on good cell service, while the rural broadband area usually unreliable causing  this  be one of the possible reasons of the low demand. To overcome this, PyBer can make a call center for the rural areas so if there is no internet connection, users can still make a call to request driver. 

If the number of drivers is too small, Pyber needs to research more on the factors which prevent the drivers from joining. They can offer better reward to attract more drivers to join Pyber.


