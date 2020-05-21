# API Challenge

This repository contains an analysis of how different weather data (cloudiness, humidity, temperature, and windiness) is impacted by a city's latitude. Additionally, VacationPy is an analysis of which cities in the world would be closest to my "ideal" weather conditions and lists a hotel in each of those cities. 

Below are scatterplots displaying the relationship (or lack thereof) between a random sample of over 500 cities' latitude and their cloudiness, humidity, temperature, and windiness.

![cloudiness](/WeatherPy/Images/LatvCloud.png)
![humidity](/WeatherPy/Images/LatvHum.png)
![temperature](/WeatherPy/Images/LatvTemp.png)
![windiness](/WeatherPy/Images/LatvWind.png)

I performed further analysis to break down the impact of a city's location in the northern or southern hemisphere changed the strength of the impact between the weather variables and a city's latitude. The below charts show these relationships, including linear regression data.

![cloudiness](/WeatherPy/Images/NorthLatvCloud.png)
![humidity](/WeatherPy/Images/NorthLatvHum.png)
![temperature](/WeatherPy/Images/NorthLatvTemp.png)
![windiness](/WeatherPy/Images/NorthLatvWind.png)
![cloudiness](/WeatherPy/Images/SouthLatvCloud.png)
![humidity](/WeatherPy/Images/SouthLatvHum.png)
![temperature](/WeatherPy/Images/SouthLatvTemp.png)
![windiness](/WeatherPy/Images/SouthLatvWind.png)

Overall Takeaways:

1. The city variable with the greatest relationship with latitude is max temperature. Temperatures rise as you move closer to the equator

2. In the northern hemisphere, humidity and max temperature are not positively correlated. It appears that as a max temperature increases, humidity decreases slightly in the northern hempisphere - at least in March.

3. One observation that could impact the outcome of this data analysis is that there are significantly more northern hemisphere cities than southern hemisphere cities. Therefore, the southern hemisphere conclusions may be slightly less reliable than the conclusions regarding the northern hemisphere.

For fun, below is a map showing the locations of hotels closest to the center of cities with meet my "ideal weather" parameters.

![hotels](/WeatherPy/Images/HotelMap.png)
