# World Weather Analysis

## Overview of the Project

This project contains of three technical analysis that were carried out using an API calls:
- Weather Data retrieved,
- Customer Travel Destinations Map created,
- Travel Itinerary Map created.

## Technical analysis
### Weather Data

For Weather Data analysis information was collected for a list of cities based on generated 2,000 random latitudes and longitudes. OpenWeatherMap API was used to request the current weather data from each unique city.

### Customer Travel Destinations Map

Travel Destination map was created based on user's preferences of a minimum and maximum temperature in the cities. Filter was used on original data of random cities, and nearby hotels were found using Google Places API. Final map was built using gmaps with marker layer added for each city. All markers contain information about the hotel name, city name, country code, current weather and a maximum temperature.

### Travel Itinerary Map

Travel Itinerary map was created using Google Directions API. Four random cities were chosen from the customer’s possible travel destinations to show the route between them. The final marker layer map is showing the route between four cities using driving travel mode, and shows pop-up markers for each city with hotel name, city name, country code, current weather and a maximum temperature.