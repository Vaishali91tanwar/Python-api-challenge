# What's weather like?
<h3>Objective:</h3>
To visualize the weather of 500+ cities across the world of varying distance from the equator. Also, plan the vacations using the analysis obtained from weather data.

<h3>Data Source:</h3>
<a href="https://openweathermap.org/api">OpenWeatherMap API</a>

<h3>Overview:</h3>
Created a Python script to pull in the weather data using OpenWeather API of 500+ cities randomly selected on the basis of latitude and longitude from citipy. 

Using Matplotlib created a series of scatter plots exploring the following relationships:

1. Temperature (F) vs. Latitude
2. Humidity (%) vs. Latitude
3. Cloudiness (%) vs. Latitude
4. Wind Speed (mph) vs. Latitude

Furthermore the linear regression aspect was analysed for the previously generated scatter plots only this time separating them into Northern and Southern hemisphere.

The weather analysis performed was then used for planning an ideal vacation. Using jupyter gmaps and Google Places API, a heatmap was generated using gmaps displaying the humidity level of each city selected for weather analysis.<br><br>
<img src="WeatherPy\heatmap.png"><br>
After narrowing down the dataframe for an ideal weather condition Google Places API was used to search for the first hotel for each city located within 5000 meters of the coordinates and the hotels were pinned on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
