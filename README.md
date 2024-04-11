Python-api-challenge

This project consisted of two parts: WeatherPy and VacationPy. WeatherPy involved analyzing weather data from various cities around the world, while VacationPy helped in planning a vacation based on ideal weather conditions.

Completed Objective:

Part 1: WeatherPy

Created Plots to Showcase the Relationship Between Weather Variables and Latitude
Used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code.

Created scatter plots to showcase the relationship between:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

Computed Linear Regression for Each Relationship

Performed linear regression analysis for the following relationships:
Northern Hemisphere: Temperature (C) vs. Latitude
Southern Hemisphere: Temperature (C) vs. Latitude
Northern Hemisphere: Humidity (%) vs. Latitude
Southern Hemisphere: Humidity (%) vs. Latitude
Northern Hemisphere: Cloudiness (%) vs. Latitude
Southern Hemisphere: Cloudiness (%) vs. Latitude
Northern Hemisphere: Wind Speed (m/s) vs. Latitude
Southern Hemisphere: Wind Speed (m/s) vs. Latitude


Part 2: VacationPy

Created a map that displayed a point for every city in the city_data_df DataFrame
Narrowed down the city_data_df DataFrame to find the ideal weather condition
For each city in the hotel_df DataFrame, used the Geoapify API to find the first hotel located within 10,000 meters of the coordinates
Added the hotel name and the country as additional information in the hover message for each city in the map.
