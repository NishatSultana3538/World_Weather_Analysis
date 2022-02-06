# World_Weather_Analysis

## Overview of the World_Weather_Analysis: 
Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in the module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.



## Results: 
### Retrieve Weather Data
Weather data was retrieved using the following code
[Weather_Database.ipynb](https://github.com/NishatSultana3538/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb)

Retrieved csv file[WeatherPy_Database.csv](https://github.com/NishatSultana3538/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv)

![DrtaFrame](https://github.com/NishatSultana3538/World_Weather_Analysis/blob/main/Weather_Database/city_df%20DataFrame.png)

### Create a Customer Travel Destinations Map
Marker layer map with pop-up markers for the cities in the vacation DataFrame is created using the code
[Vacation_Search.ipynb](https://github.com/NishatSultana3538/World_Weather_Analysis/blob/main/Vaccation_Search/Vacation_Search.ipynb)
![DrtaFrame](https://github.com/NishatSultana3538/World_Weather_Analysis/blob/main/Vaccation_Search/hotel_df%20DataFrame.png)
Retrieved csv file[WeatherPy_vacation.csv](https://github.com/NishatSultana3538/World_Weather_Analysis/blob/main/Vaccation_Search/WeatherPy_Vacation.csv)
![WeatherPy_vacation_map](https://github.com/NishatSultana3538/World_Weather_Analysis/blob/main/Vaccation_Search/WeatherPy_vacation_map.png)


### Create a Travel Itinerary Map
Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary. The Jupyter Notebook file used here to get the data was
[Vacation_Itinerary.ipynb](https://github.com/NishatSultana3538/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb)
 The directions layer map

 ![direction a_layer_map](https://github.com/NishatSultana3538/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

 The marker layer map with a pop-up marker for each city 
 ![marker_layer_map](https://github.com/NishatSultana3538/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)


[]()

 
The csv data used here is [city_data.csv](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/Resources/city_data.csv)
 & 
[ride_data.csv](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/Resources/ride_data.csv)


![PyBer_fare_summary_unformatter](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/PyBer_unformatted.png)



![PyBer_Summary_formatted](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/PyBer_Summary_formatted.png)


![pivot _dataframe](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/dataframe_pivot.png)

resampled_dataframe.png)

Finally, the line graph I got is as below:

![PyBer-fare_line_graph](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)





## Summary: 

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types.

1. Decreasing fares in rural and suburban areas respectively could increase the total revenue in those areas as the income of riders are usually lower in those areas.
2. Giving some  weekly perks could influence people to use more of the ride share.
3. Making a monthly subscription with 10-15% discounts could make the riders in rural and suburban areas to use more ride share.

### Conclusion 
The line graphs made from the ride-sharing data by city types helps to understand the disparities in city types and help the business make dicisions accordingly.









## Results: 
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types-


Here in PyBer analysis project I create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, I create a multiple-line graph that shows the total weekly fares for each city type. The code I use to get the line charts  
[PyBer_Challenge](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

 
The csv data used here is [city_data.csv](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/Resources/city_data.csv)
 & 
[ride_data.csv](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/Resources/ride_data.csv)

First I create a PyBer summary table with all the data gathered from the merged dataframe
![PyBer_fare_summary_unformatter](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/PyBer_unformatted.png)

I formatted the Pyber summary DataFrame to look like below: 

![PyBer_Summary_formatted](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/PyBer_Summary_formatted.png)

Using Pandas skills and two new functions, pivot() and resample(), I created a multiple-line graph that shows the total fares for each week by city type.
The dataframe after using pivot functions look like below:

![pivot _dataframe](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/dataframe_pivot.png)

I create a new DataFrame by applying the resample() function and resample the data in weekly bins, then apply the sum() method to get the total fares for each week the dataframe look like below:

![resampled_dataframe](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/resampled_dataframe.png)

Finally, the line graph I got is as below:

![PyBer-fare_line_graph](https://github.com/NishatSultana3538/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)


From the above line charts we can see that urban cities has the highest total fares among the city types and rural cities has the lowest total fares among the city types.


## Summary: 

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types.

1. Decreasing fares in rural and suburban areas respectively could increase the total revenue in those areas as the income of riders are usually lower in those areas.
2. Giving some  weekly perks could influence people to use more of the ride share.
3. Making a monthly subscription with 10-15% discounts could make the riders in rural and suburban areas to use more ride share.

### Conclusion 
The line graphs made from the ride-sharing data by city types helps to understand the disparities in city types and help the business make dicisions accordingly.







