# World_Weather_Analysis

### Overview

This project named PlanMyTrip is designed to collect and analyze weather data across cities worldwide, with the purpose to use the data to recommend ideal hotels based on clients' weather preferences.

We created a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

### Weather Data

First we retrieve the weather data by generating a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with OpenWeatherMap to gather the current weather description for each city. Then, create a new DataFrame containing the updated weather data.

### Vacation Search

Then we will employ input statements to retrieve customer weather preferences. Next, with those preferences we will identify potential travel destinations and nearby hotels. Finally, we will show those destinations on a marker layer map with pop-up markers.

<img width="442" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/113747210/200963610-4b1f29b1-04f3-45d0-a1b2-24e36c2d102b.png">

### Vacation Itinerary

Finally we create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, we'll create a marker layer map with a pop-up marker for each city on the itinerary.

<img width="442" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/113747210/200964035-1fc91769-8c31-427e-9348-c7686a853f5b.png">



