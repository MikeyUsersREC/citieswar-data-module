# Cities War Data Module

> ## Please make sure to establish an Issue if you want me to update this data.

CitiesWar is a multiplayer online game based on Google Maps where you can control the real city in the world.

(I did not make Cities War, however I would like to use this repository for a city data hub for aspiring Web Developers and Discord Bot Developers).


Python code for Integration:

```py
import requests

url = 'https://raw.githubusercontent.com/MikeyUsersREC/citieswar-data-module/master/PUT-FILENAME-HERE'
<!-- Replace "Put-Filename-Here" with the data you want to use. -->
page = requests.get(url)
print page.text
```
