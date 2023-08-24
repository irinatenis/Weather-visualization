# Visualization of weather of over 500 cities of varying distances from the equator
The projects consists of two parts:

## ***Part 1.***
To analyse a dataset that includes data coordinates and weather conditions for over 500 cities of varying distances from the equator. The goal is to to create a representative model of weather across the cities.
#### Technology
Jupiter notebook; libraries: pandas, citipy, numpy, requests, time, json, scipy.stats, matplotlib; OpenWeatherMap API
#### Tasks completed
- Used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code.
- Created plots to showcase the relationship between weather Variables and latitude.
- Computed linear regression for each relationship.

## ***Part 2.***
To use the weather data from Part 1 to plan future vacations: narrow down the places to the ones that meet my requirements for the ideal vacation place and create map visualizations.
#### Technology
Jupiter notebook; libraries: hvplot, pandas, requests geoViews; Geoapify API
#### Tasks completed
- Created a map that displays a point for every city in the city_data_df DataFrame. 
- Narrowed down the city_data_df DataFrame to find my ideal weather condition.
- Used the Geoapify API to find the first hotel located within 10,000 metres of my coordinates and created a map with a hjover message for each city.



