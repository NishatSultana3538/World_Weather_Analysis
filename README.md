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















