# World_Weather_Analysis

## Purpose
The purpose of this analysis was to create a vacation map that allows users to identify travel destinations by filtering certain weather conditions that suits the user. Utilizing Google API's, recommendations were also provided to the user on ideal hotels within their preferred travel destinations.

## Overview
In order to create the vacation map, a generated a list of 2000 random latitudes and longitudes were created. With the coordinates generated,a list of the nearest cities were retrieved and compiled  using the imported citipy module. The OpenWeatherMap API was used to request the current weather data from each unique city on the list. The resulting map provides users with descriptions of the destinations found on our list, including: hotel name, city, country, and current weather and description.
