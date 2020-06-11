# python-api-challenge

## Part I - WeatherPy

* Your final notebook must:

	* Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
	* Perform a weather check on each of the cities using a series of successive API calls.
	* Include a print log of each city as it's being processed with the city number and city name.
	* Save a CSV of all retrieved data and a PNG image for each scatter plot.


## Part II - VacationPy

* As final considerations:

	* Create a heat map that displays the humidity for every city from the part I of the homework.
	* Narrow down the DataFrame to find your ideal weather condition. For example:
		* A max temperature lower than 80 degrees but higher than 70.
		* Wind speed less than 10 mph.
		* Zero cloudiness.
		* Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.
		* Note: Feel free to adjust to your specifications but be sure to limit the number of rows returned by your API requests to a reasonable number.
	* Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
	* Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
