# World_Weather_Analysis
Week 6, Python API's

This assignment is broken down into two deliverables. It also uses a gitignore file for the API variables.

The first deliverable is the WeatherPy notebook where a Python script is written to visualize the weather of over 500 cities of varying distances from the equator. The data from the 500 cities extracts certain elements to be visualized and places them in a new data frame which was then saved as a new CSV file.

Plots were then created to showcase the relationship between different weather variables and latitude to determine relationships. The only distinguishable relationship discovered in this activity was that the temperature is higher towards a latitude of 0 for both the Northern and Southern Hemisphere. There were no coorelations found for latitude and humidity, cloudiness, or wind speed.

The second deliverable is the VacationPy notebook where the use of the previous CSV file created is used with geoViews in the Python Library as well as the Geoapify API.

This notebook cleans out any null data from the CSV created in the initial Weather notebook. Then, a new DataFrame is created to display narrowed information along with specific weather requirements to search for hotels within a certain radius of the narrowed data. The parameters of the hotel DF are reduced to a limit of 20 searches so as to avoid excessive API requests. Depending on the desired locations or weather information, this search could be narrowed further and limits of the search could be adjusted for a more specific region or more specific weather requirements.

Finally, the searches that returned hotels within the specified radius are displayedin a new map plot with the specified requirements of Lng, Lat, City, Humidity, Hotel Name, and Country.