# Weather and vacation

This code is divided in two parts, WeatherPy gets data from a set of random cities. After plotting realtionships and correlations, VacationPy generates a map with a set of personal vacation spots.

### WeatherPy
WeatherPy uses Citipy to find the nearest city to a random set of latitude and longitude coordinates. After cleaning the data, plots of the relation between latitude and maximum temperature, humidity, cloudiness, and wind speed are shown along with an explanation. Then the data is divided by Northern and Southern hemispheres, same relations are plotted, except this time the correlation and regression are added to the plots. 

### VacationPy
VacationPy uses the clean data from WeatherPy and Google maps to plot a heat map of the humidity of all the cities. It then filters the data and gets cities that meet vacation conditions. Next, it finds a lodge in those cities and marks them on the map.
