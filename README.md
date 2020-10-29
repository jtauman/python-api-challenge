# python-api-challenge

## Weather by Latitude

This challenge was designed to answer the question: "What is the weather like the closer we get to the equator?". The OpenWeatherMap API (https://openweathermap.org/api) was queried on the current weather conditions for 554 randomly selected cities around the globe on July 13, 2020 at approximately 9:00pm EDT. For each city, the maximum daily temperature (F), % humidity, % cloudiness, and windspeed(mph) were returned along with the city's latitude and longitude coordinates.


The data was organized and processed using the Python Pandas library and Matplotlib was used to visualize the different types of weather data obtained with respect to latitude.  Regression analysis was used to assess the correlation of the different weather variables with latitude in the Northern and Southern hemispheres separately.  The analysis is located in the jupyter notebook file: weatherPy_main.ipynb

## Ideal Vacation Destination

This challenge was designed to use weather data from OpenWeatehrMap API to plan an ideal vaction destination.  The data frame consisting of weather data from the 554 random cities in the Weather by Latitude challenge was filtered to obtain a subset of data based on my ideal weather conditions (temperature between 68-83 F, humidty < 60%, cloudiness < 20%, and windspeed between 5-10 mph).  Google Places API was used to find the first hotel for each city located within 5000 meters of your coordinates and each hotel was plotted on a global map overlayed with a humidity heat map for the 10 cities that matched my filter criteria. 





