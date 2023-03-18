# World_Weather_Analysis

## Background
In preparation for this project, I needed to help collect and present data for a travel tech company called PlanMyTrip, which specializes in internet-related services in the hotel and lodging industry. Customers use PlanMyTrip's search feature to filter based on their preferred travel criteria in order to find their ideal hotel anywhere in the world. 

To perform this task, I used Jupyter Notebook and the CitiPy module to get the cities for more than 500 random latitudes and longitudes. Then, I performed requests on the OpenWeatherMap API and retrieved the JSON weather data from these cities. The weather data was then added to a Pandas data frame, where I used Matplotlib to create a series of scatter plots to show the relationship between the latitude and a variety of weather parameters for over 500 cities around the world.

As part of my analysis, you needed to perform statistical calculations on the data using linear regression on the weather parameters in the Northern and Southern hemispheres. This data was meant to help the team predict the best time of year for people to plan their vacation. Finally, I exported the data, cleaned it, and used the weather data to choose the best cities for vacation based on certain weather criteria, and then mapped these cities using GeoViews and the Geoapify API. 

## Project Objective

This project involved the addition of the weather description to the weather data to the PlanMyTrip app. The idea is to use the weather description data already retrieved previously to enhance the PlanMyTrip app. Then, allow users to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. The users will choose four cities from the list of potential travel destinations to create a travel itinerary. Finally, using the Google Maps Directions API, a travel route between the four cities and a marker layer map were created.

## Deliverables

### Deliverable 1: Retrieve Weather Data

To generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with OpenWeatherMap. In addition to the city weather data gathered previously, I used my API skills to retrieve the current weather description for each city. Then, created a new DataFrame containing the updated weather data.

<img width="785" alt="Deliv1_DF" src="https://user-images.githubusercontent.com/114960958/226145736-67c925b5-603c-4c5a-90b2-a0c04f5dc5a6.png">


### Deliverable 2: Create a Customer Travel Destinations Map



### Deliverable 3: Create a Travel Itinerary Map
