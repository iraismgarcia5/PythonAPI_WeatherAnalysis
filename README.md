# Python API - What's the Weather Like as We Approach the Equator?

In this project, I was tasked with creaitng a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilitzed a simple Python library and the OpenWeatherMap API to create a representative model of weather across world cities.

I built plots to showcase the following relationships:
* Temperature (F) vs. Latitude

![Image](https://github.com/iraismgarcia5/PythonAPI_WeatherAnalysis/blob/master/Latitude_vs_Temperature.png)

* Humidity (%) vs. Latitude

![Image](https://github.com/iraismgarcia5/PythonAPI_WeatherAnalysis/blob/master/Latitude_vs_Humidity.png)

* Cloudiness (%) vs. Latitude

![Image](https://github.com/iraismgarcia5/PythonAPI_WeatherAnalysis/blob/master/Latitude_vs_Cloudiness.png)

* Wind Speed (mph) vs. Latitude

![Image](https://github.com/iraismgarcia5/PythonAPI_WeatherAnalysis/blob/master/Latitude_vs_WindSpeed.png)

Finally, I was tasked with drawing conclusions from the plots.

*Observations:*

* From the Latitude vs. Temperature plot, we can see that the maximum temperature gets hotter as the latitude approaches 0
* It seems, from the Latitude vs. Humidity plot, that humidity is lower when latitudes are at around the midpoint between latitude 0 and the minimum and maximum latitude
* In the Latitude vs. Cloudiness plot, there seems to be not much correlation, as cloudiness is present (or not) in cities at almost any latitude
