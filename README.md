# python-api-challenge

WeatherPy:

A Python script has been created to visualize the weather of 500+ cities across the world of varying distance from the equator.  For this task, a simple Python library, the OpenWeatherMap API, and a little common sense has been utilized to create a representative model of weather across world cities.

The first demonstration is a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

After each plot, a sentence explaining what the code is analyzing was added.

The second requirement is to run linear regression on each relationship. The data was separated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude) and the following were plotted:

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

VacationPy:

A heat map that displays the humidity for every city from Part I was created.

The DataFrame to find your ideal weather condition was narrowed using the following criteria:
- A max temperature lower than 80 degrees but higher than 70.
-Wind speed less than 10 mph.
-Zero cloudiness.
-Any rows that don't contain all three conditions were dropped making sure the weather is ideal.

Using Google Places API, the first hotel for each city located within 5000 meters of the coordinates were found.

The hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country were plotted.