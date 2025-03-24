# python-api-challenge
---
### Part 1: WeatherPy
In this part of the challenge, I generated random latitude and longitude combinations. Then, I used citipy to find the closest city and its name. It should be noted that all the cities in citipy have a populatoin of at least 5000. The next step involed using the OpenWeatherMap API to geocode those cities and log their respective latitude and longitude values, as well as other key information about the city's weather, such as, the max temperature and the humidity. After that, I converted the data I collected into a pandas DataFrame and created several charts to look for correlations between the latitude of the city key data points like humidity, cloudiness, wind speed, and max temperature. Finally, I created a function that determined the correlation coefficient and created new charts with the regression line included. 

---
### Part 2: VacationPy
For the second part, I took the pandas DataFrame from WeatherPy and created a chart that plotted each city on the map with its size being dependant on the percentage of humidity. I then filtered out cities that I thought wouldn't be enjoyable to visit. After completing that, I used Geoapify API to find the nearest hotel in those desired cities. I then finished this project off by adding the closest hotel name and the country to the hover message for each city. 

---
### Citations
- Use and read about [OpenWeatherMap API](https://openweathermap.org/api)
- Use and read about [Geoapify API](https://www.geoapify.com/)
- Download [citipy](https://pypi.org/project/citipy/) or read about it [here](https://github.com/wingchen/citipy)
