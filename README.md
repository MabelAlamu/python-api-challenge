# python-api-challenge

#Part I: WeatherPy

We'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator utilizing a simple Python library and the OpenWeatherMap API



The first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude
      

The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

 * Northern Hemisphere - Temperature (F) vs. Latitude
 * Southern Hemisphere - Temperature (F) vs. Latitude
 * Northern Hemisphere - Humidity (%) vs. Latitude
 * Southern Hemisphere - Humidity (%) vs. Latitude
 * Northern Hemisphere - Cloudiness (%) vs. Latitude
 * Southern Hemisphere - Cloudiness (%) vs. Latitude
 * Northern Hemisphere - Wind Speed (mph) vs. Latitude
 * Southern Hemisphere - Wind Speed (mph) vs. Latitude


The final notebook should contain:

 * Randomly selected, at least 500 unique (non-repeat), cities based on latitude and longitude.
 * A weather check on each of the cities using a series of successive API calls.
 * A print log of each city as it's being processed with the city number and city name.
 * Save a CSV of all retrieved data and a PNG image for each scatter plot.


#Part II: VacationPy


Using jupyter-gmaps and the Google Places API let's use weather data to plan future vacations.


Note: Remember that any API usage beyond the $200 credit will be charged to your personal account. You can set quotas and limits to your daily requests to be sure you can't be charged. Check out Google Maps Platform Billing and Manage your cost of use for more information.


Note: if you having trouble displaying the maps, try running jupyter nbextension enable --py gmaps in your environment and retry.


To complete this part of the assignment,you will need to do the following:
       
 * Create a heat map that displays the humidity for every city from Part I.
 * Narrow down the DataFrame to find your ideal weather condition. Note: Feel free to adjust to your specifications but be sure to limit the number of rows returned by your API requests to a reasonable number.
 * Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
 * Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
