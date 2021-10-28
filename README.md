# World Weather Analysis

## Overview of Analysis

This project is a demonstration of how to use various APIs to gather information about the current weather from random locations using the OpenWeatherMap API and learning the many usages of APIs available from Google Maps. The purpose of this analysis is to generate random location all over the world and then using the generated latitudes and longitudes to gather relavent weather information about each location with assistence of the OpenWeatherMap API. Gathering the various weather information about each of the locations, can create a bunch of visualizations about how the cloudiness, wind speed, maximum temperature, minimum temperature, humidity vary based on latitude. Regression analysis of each plot showed if variation in the variables above were significantly impacted by latitude. With the assistence of the APIs from Google Maps, the city, country, and weather information are used to create heatmaps based off of all of the weather variables.
![Hotel Markers Map](https://github.com/likenberry/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)
The closest hotels to the various cities could be found using Google Maps again. Another important step for this analysis was using try and except blocks to handle large blocks code that have to iterate multiple times. Try and except blocks are used to allow the code to keep running even when an error is encountered. The hotel data was added a heat map with a marker for each hotel on the map. Finally, travel routes between city destinations using the Directions API from Google Maps and specifying DRIVING, WALKING and BICYCLING. Below is an example of a travel route around Australia.
![Australia Travel Route](https://github.com/likenberry/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

## Resources

- Data Source: Open Weather Map, Google Maps
- Software: Python 3.6.1, Visual Studio Code 1.61.0, Jupyter Notebook
