# World_Weather_Analysis

## Overview
- Collect and analyze weather data across cities worldwide
- **PlanMyTrip** (Client application) will use the data from the **OpenWeatherMap API** to identify ideal hotels based on the user's weather preferences

## Requirements
- Use the **Pandas** library to create a dataframe with 500 unique cities and their weather data in real time.
- Use **NumPy** and **random** to generate random latitude and longitude locations.
- Use **citypy** to list the nearest city locations from the random locations.
- Use **OpenWeatherMap API** to request current weather data for each city (Data retrieved in JSON format).

### Steps
1. Collect the Data
    - Parse the JSON into a DataFrame with:
      - City, country & date
      - Latitude and Longitude
      - Maximum Temperature
      - Humidity
      - Cloudiness
      - Wind speed
2. Exploratory analysis with data visualization
    - Use **Matplotlib** to create scatter plots for the following:
      - Latitude vs Temperature
      - Latitude vs. Humidity
      - Latitude vs. Cloudiness
      - Latidude vs. Wind Speed
    - Find any correlations from the above comparisons.
3. Visualize the travel data
    - Visualize as heatmaps using the **Google Maps and Places API**
      - Filter the DataFrame based on user inputs for Minimum and Maximum Temperature.
      - Find hotels from the city coordinate using **Google Maps and Places API** and Search Nearby feature.
      - Store the hotel in the DataFrame.
      - Add popup markers to the heatmap that display information about the City, Current Maximum Temperature and a hotel in the city. 

### Revisions
1. Add **weather description** to weather dataframe
2. Use input statements to filter data for weather preference
3. Allow user to create an intinerary of four cities from the list of potential travel destinations
4. Create travel route between the four cities

### Deliverables
1. Create DataFrame with 2000 random latitude and longitudes and retrieve the nearest city and weather data. Export the DataFrame as 'WeatherPy_Database.csv'.
2. Use input statements to retrieve customer weather preferences and filter potential travel destinations and nearby hotels. Display the destinations on a marker layer map with pop-up markers. 
3. Use the Google Directions API to create a travel itinerary with routes between four cities from the customer's chosen destinations.

### Software
- python 3.7
- Jupyter Notebook
- gmaps plugin

### Dependencies
- pandas
- numpy
- requests
- time
- citipy
- matplotlib

### APIs
- OpenWeatherMap (Requires Key)
- Google Maps Directions (Requires Key & Credit Card info)

### Documentation Links
[OpenWeatherMap Current Weather API](https://openweathermap.org/current)
[Google Directions API](https://developers.google.com/maps/documentation/directions/overview)
[gmaps](https://jupyter-gmaps.readthedocs.io/en/latest/tutorial.html#directions-layer)
[to_numpy](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_numpy.html)
[concat](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.concat.html)

## Results

### Deliverable 1: Weather Database


### Deliverable 2: Vacation Map with Markers


### Deliverable 3: Travel Itinerary Map


