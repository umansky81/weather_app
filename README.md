# weather_app
Weather App Project - DS20 - Yonatan Umansky

This first python project of DS20 course is a Streamlit web application that acts as a weather dashboard.
It allows users to get current and forecasted weather data for a specific location. 
Users can input a city name or select a location directly on an interactive Folium map.
Once a location is chosen, the app fetches real-time weather details and a five-day forecast from the OpenWeatherMap API. 
It presents this information with different units (metric or imperial), complete with a visual summary of key metrics and a forecast for the coming days. 
Additionally, it uses the Meteostat library to retrieve historical temperature data for a nearby weather station and then plots this historical average against the upcoming five-day temperature forecast.

In order to see proper data as accurate as possible, please add next to the desired city the country prefix.
For example - if you wish to see data for Paris, enter the following in the input box: "Paris FR".
Otherwise choose a location anywhere on the map.

You may choose whether to see the data in imperial or metric units by selecting the desired unit in the radio button.

Please note that once a location is chosen using one of the methods (map or text input), it is not possible to choose another location using the other method, but rather only by using the same method.
This is a technical difficulty I have been facing during my work and so far I could not come up with a proper solution for this issue.
Hopefully you will still be able to enjoy using this app.

The app is entirely executed in the 'Main.py' file.

Sincerely,
Yonatan Umansky