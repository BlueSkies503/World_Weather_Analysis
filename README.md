# World_Weather_Analysis

## Overview
This application is used to help plan trips.

We start by randomly generating 2,000 latitude and longitude coordinate pairs, and then finding the closest city to each of those coordinates. We then get the current weather conditions for each of those cities and store all the information in a database.

We then prompt the user to filter this database based their preferred minimum and maximum temperatures for each of their destinations. We then use this filtered database to search for nearby hotels. A google map is then generated showcasing all hotels in the database.

Four nearby locations are then selected, and another google map is generated showing a route from one location to the next, ending back where you started.