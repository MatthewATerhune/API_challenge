# API_challenge -- 
In this example, i'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, i'll be utilizing a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.
The first requirement is to create a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude <br>
Humidity (%) vs. Latitude <br>
Cloudiness (%) vs. Latitude <br>
Wind Speed (mph) vs. Latitude <br>

I then ran linear regression on each relationship. This time, i will separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude <br>
Southern Hemisphere - Temperature (F) vs. Latitude <br>
Northern Hemisphere - Humidity (%) vs. Latitude <br>
Southern Hemisphere - Humidity (%) vs. Latitude <br>
Northern Hemisphere - Cloudiness (%) vs. Latitude <br>
Southern Hemisphere - Cloudiness (%) vs. Latitude <br>
Northern Hemisphere - Wind Speed (mph) vs. Latitude <br>
Southern Hemisphere - Wind Speed (mph) vs. Latitude <br>

![plot](./Weatherpy_North_Max_temp_lregress.png) <br>

Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.


Part II - VacationPy
Now let's use our skills in working with weather data to plan future vacations. Use jupyter-gmaps and the Google Places API for this part of the assignment.

Create a heat map that displays the humidity for every city from Part I.


![plot](./hotel_map.png)
