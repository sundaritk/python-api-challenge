# python-api-challenge

## Part I - WeatherPy

* The code for this challenge has:

	* Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
	* Weather check on each of the cities using a series of successive API calls.
	* Includes a print log of each city as it's being processed with the city number and city name.
	* A CSV file with retrieved data and a PNG image for each scatter plot.


## Part II - VacationPy

* The code for this challenge has:

	* Created a heat map that displays the humidity for every city from the part I of the homework.
	* Narrowing down the DataFrame to find your ideal weather condition. For example:
		* A max temperature lower than 80 degrees but higher than 70.
		* Wind speed less than 10 mph.
		* Zero cloudiness.
		* Dropping any rows that don't contain all three conditions.
	* Using Google Places API,locate the first hotel for each city located within 5000 meters of your coordinates.
	* Plotting the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
