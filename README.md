# World Weather Analysis

## Overview of the project 
The purpose of this project is to create the customer customized travel map by using the weather data from openweathermap.org within API. Specifically, customer will type the minimum and maximum temperature that they want to stay during the travel and by using the API system, we will automically clear out the areas that do not match the customer's condition. Additionally, we provide the traveling routine either by 'diriving', 'walking' or 'bicycle'. Overall, we analyzed the following technical features: 
* Weather Data Reserach 
* Customer Customized Travel - Hotel & Map 
* Customer Customized Traveling Itinierary Map 

## Weather Data Research 
A weather database has been created by use of API from openweathermap.org and retreived 2000 sets of random latitudes and longtitudes. By using the latitudes and longtitudes, we can get the exact location of each city from each country. 
<img width="714" alt="Screen Shot 2022-04-04 at 6 07 24 PM" src="https://user-images.githubusercontent.com/83077836/161640013-272cadf6-fde5-495d-ac0e-8ba5bd6e7ec8.png">

The weather description can be altered in the future becasue weather description, wind speed, humidity, and cloudiness are all current situation. 

## Customer Customized Travel - Hotel & Map 
<img width="776" alt="Screen Shot 2022-04-04 at 6 09 02 PM" src="https://user-images.githubusercontent.com/83077836/161640177-4796eed1-e9a7-484d-af8b-e869a3223e99.png">

We let customers enter the minimmum and maximum temperature and we find the appropriate locations randomly around the world based on the temperature customer has entered. We have found the hotels for each location that matches customer's need. 
<img width="802" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/83077836/161640352-337a699f-d754-4a0f-93c7-ab8be5e8455d.png">

## Customer Customized Travel Itinerary Map 
A Travel Itinerary map shows the route between customer selected four cities from using the Google Directions API. We set the starting and ending city identically and shows the fastest routine to travel between the four cities. 

<img width="949" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/83077836/161640743-be77eae1-063b-4acb-b342-709638c52440.png">
<img width="978" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/83077836/161640747-4f3e66e6-db7c-413c-bf9a-8f6d228fef01.png">
