### Part 1: WeatherPy
In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python library Links to an external site., the OpenWeatherMap API Links to an external site., and your problem-solving skills to create a representative model of weather across cities.

For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

# Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

    a. Latitude vs. Temperature ***

    b. Latitude vs. Humidity ***

    c. Latitude vs. Cloudiness ***

    d. Latitude vs. Wind Speed ***

# Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values.
 
    a. Northern Hemisphere: Temperature vs. Latitude ***

    b. Southern Hemisphere: Temperature vs. Latitude    ***

        + Explain what the linear regression is modeling. Describe any relationships. 

    c. Northern Hemisphere: Humidity vs. Latitude   ***

    d. Southern Hemisphere: Humidity vs. Latitude   ***

        + Explain what the linear regression is modeling. Describe any relationships. 

    e. Northern Hemisphere: Cloudiness vs. Latitude ***

    f. Southern Hemisphere: Cloudiness vs. Latitude ***

        + Explain what the linear regression is modeling. Describe any relationships. 

    g. Northern Hemisphere: Wind Speed vs. Latitude ***

    h. Southern Hemisphere: Wind Speed vs. Latitude ***

        + Explain what the linear regression is modeling. Describe any relationships. 

#######################################################################################

### Part 2: 

1. Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city. ****

2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:    ***

    a. A max temperature lower than 27 degrees but higher than 21 ***

    b. Wind speed less than 4.5 m/s ***

    c. Zero cloudiness  ***

3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

5. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
