# World Weather Analysis

## Overview

This repository is setup to share data for a project where weather for cities correlating to randomly generated longitudial and latitudinal geographic coordinates, was filtered by user input and possible hotels and mock travel maps were generated using OpenWeather and Google Maps APIs.

## Results

Using the APIs from OpenWeather and Google, 2000 randomly generated latitudes and longitutudes were mapped to cities using the citipy module. This map shows markers for all of the cities resulting from that filtering process. Clicking on a marker will display the closest hotel to the site as well as city name, country, hotel name, and current weather. 

![Map of cities selected by user criteria](https://github.com/MattK1454/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

This map shows a possible travel route for 4 city locations in Mexico. This was done using the "Directions API" from Google.

![Mock up of possible trip around Mexico](https://github.com/MattK1454/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

This map shows the data markers displayed for all the sites on the mock trip in Mexico.

![Mexico trip sites with weather data](https://github.com/MattK1454/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

## Summary

Using the code from the Module 6 lessons, it was possible to generate, filter, and hotels for cities with desirable weather. This mapping all of this data was possible using APIs from OpenWeather and Google Maps and Places. It is possible to see how this code could be used to generate possible vacation travel plans based on desired weather parameters.
