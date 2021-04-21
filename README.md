# python-api-challenge
Python API Assignment:

This assignment sets out to answer a fundamental question: "What's the weather like as we approach the equator?"

Inside this repository you will find:
* "WeatherPy" a directory holding two jupyter notebook files that contain the main scripts to run for analysis.
    * WeatherPy.ipynb
    * "output_data" a directory that contains:
        * cities.csv - a file of all cities retrieved weather data in WeatherPy.ipynb
        * 4 scatter plots showing relationships:
            * Temperature (F) vs. Latitude
            * Humidity (%) vs. Latitude
            * Cloudiness (%) vs. Latitude
            * Wind Speed (mph) vs. Latitude
        * 8 scatter plots with linear regression on each relationship for both Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
            * Northern Hemisphere - Temperature (F) vs. Latitude
            * Southern Hemisphere - Temperature (F) vs. Latitude
            * Northern Hemisphere - Humidity (%) vs. Latitude
            * Southern Hemisphere - Humidity (%) vs. Latitude
            * Northern Hemisphere - Cloudiness (%) vs. Latitude
            * Southern Hemisphere - Cloudiness (%) vs. Latitude
            * Northern Hemisphere - Wind Speed (mph) vs. Latitude
            * Southern Hemisphere - Wind Speed (mph) vs. Latitude
    * Vacation.ipynb 
        * Screen shot of heat map that displays the humidity for every city in the cities.csv file.
        * Screen shot of the humidity heatmap with hotel pins/markers containing ideal weather cities Hotel Name, City, and Country.

***
## Usage:
Run WeatherPy.ipynb in the WeatherPy directory with Jupyter Notebook to visualize the weather of 500+ cities across the world of varying distance from the equator using a simple Python library and the OpenWeatherMap API. Includes a written description of three observable trends based on the data at the top of the notebook. 
 * Outputs 12 plots and one csv file

Run VacationPy.ipynb in the WeatherPy directory with Jupyter Notebook to assist in planning future vacations using jupyter-gmaps and the Google Places API. Uses the weather data retrieved in WeatherPy.ipynb, creates a humidity heat map, and then narrows down the cities to meet ideal conditions for a vacation spot.  The conditions are:  max temperature lower than 80 degrees but higher than 70, wind speed less than 10 mph and zero cloudiness.  Then it finds hotels within 5000 meters of the filtered cities latitude and longitude coordinates.  Finally, the humidity heat map is created with pins/markers showing hotel name, city and country on that map.
* two screenshots of heat maps are included

