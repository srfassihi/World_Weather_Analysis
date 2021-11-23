# World_Weather_Analysis

## Overview
- Collect and analyze weather data across cities worldwide
- **PlanMyTrip** (Client application) will use the data from the **OpenWeatherMap API** to identify ideal hotels based on the user's weather preferences

## Requirements
- Use the **Pandas** library to create a dataframe with 500 unique cities and their weather data in real time.
- Use **NumPy** and **random** to generate random latitude and longitude locations.
- Use **citypy** to list the nearest city locations from the random locations.
- Use **OpenWeatherMap API** to request current weather data for each city (Data retrieved in JSON format).
- Parse the JSON into a DataFrame with:
  - City, country & date
  - Latitude and Longitude
  - Maximum Temperature
  - Humidity
  - Cloudiness
  - Wind speed
- Use **Matplotlib** to create scatter plots for the following:
  - Latitude vs Temperature
  - Latitude vs. Humidity
  - Latitude vs. Cloudiness
  - Latidude vs. Wind Speed
- Find any correlations from the above comparisons.
- Visualize as heatmaps using the **Google Maps and Places API**
  - Filter the DataFrame based on user inputs for Minimum and Maximum Temperature.
  - Find hotels from the city coordinate using **Google Maps and Places API** and Search Nearby feature.
  - Store the hotel in the DataFrame.
  - Add popup markers to the heatmap that display information about the City, Current Maximum Temperature and a hotel in the city.     

### Steps
1. Collect the data
2. Exploratory Analysis with Visualization
3. Visualize Travel Data

### Software
- python 3.7
- Jupyter Notebook

### Dependencies
- pandas
- random
- numpy
- citypy
- matplotlib

## Results
