# python-api-challenge

### Part 1: WeatherPy
Create a Python script to visualize the weather of over 500 cities of varying distances from the equator using the citipy Python libraryLinks to an external site, and the OpenWeatherMap APILinks to an external site. Create a representative model of weather across cities.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
- Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude)
- Create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values
- Northern/Southern Hemisphere: Temperature vs. Latitude
- Northern/Southern Hemisphere: Humidity vs. Latitude
- Northern/Southern Hemisphere: Cloudiness vs. Latitude
- Northern/Southern Hemisphere: Wind Speed vs. Latitude

### Part 2: VacationPy
Use Jupyter notebooks, the geoViews Python library, and the Geoapify API to plan future vacations.

- Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
- Narrow down the city_data_df DataFrame to find your ideal weather condition.
- Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
- For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
- Add the hotel name and the country as additional information in the hover message for each city on the map.

