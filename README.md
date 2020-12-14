# python-api-challenge

* citipy (https://pypi.org/project/citipy/)
citipy is a comprehensive dataset storing information such as name, country, and geographic coordinates (latitude and longite) of worldwide cities.

* OpenWeather (https://openweathermap.org/) 
OpenWeather is a platform provides historical, current and forecasted weather data. Its Current Weather Data allows live data call from over 200,000 cities at any locations, by using its in-house developed API. The responsed data is available in various format such as JSON, returns information including city name, geographic coordinates, and current weather (e.g. temperature, humidity, wind, and clouds), making it an extremely useful tool for itinerary planning.

* Google Place API (https://developers.google.com/places/web-service/overview)
Google Place API is a service under the Google Maps Platform, to facilitate place search with more detailed/specific information as well as to permit the access to substantial number of related photos stored in its database.

* jupyter-gmaps (https://jupyter-gmaps.readthedocs.io/en/latest/index.html)
gmaps is a Jupyter plugin for embedding Google Maps in Jupyter notebooks. Its concept of adding layers (e.g. marker, symbol, heatmap) and information display to a base map greatly improves map visualization.

## WeatherPy
By combining the abovementioned tools, coupled with other powerful Python packages (pandas, matplotlib, scipy, etc), this project aimed to assess the weather from a large sample set of randomly selected cities with varying distances from the equator, in order to explore the general trend/ potential associations between latitude and several main components of weather (temperature, humidity, wind, and cloudiness).

## VacationPy
After retrieving the current weather data from a large number of cities worldwide, it would be rationale to choose the ones with the best weather conditions for a vacation plan. Google Place API hence came up with the fastest and easiest way to search and locate for hotels for the short term accommodation. Jupyter Gmaps at the same time helped to mark the name and location of each place on the map.
