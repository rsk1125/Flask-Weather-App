# Flask-Weather-App

Just a simple weather app built using the Flask framework for Python, as well as the OpenWeatherMapAPI

Displays current weather conditons, location, coordinates, pressure and humidity, 
as well as having a search feature that can take city and zipcode input
(default city on start-up is Tallahassee)

Ensure you have the required modules installed, unzip the file and run weather.py.
You will get a local url to enter into your browser to access the app

Modules used/required:
-Flask (Flask, render_template, request)
-datetime
-json
-urllib.request

API:
OpenWeatherMap

Known issues:
Currently search feature only supports single words for cities, as entering any spaces
will cause a 404 when entered in the search feature.
The current workaround is using the unicode for space, which is %20
