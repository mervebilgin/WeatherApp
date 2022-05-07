# WeatherApp
### Current Weather App with JavaScript ###

I have developed an application where we can access the current weather of cities with JavaScript. I used dynamic information retrieved via [OpenWeather](https://openweathermap.org/api) API on the website. Weather information can be retrieved daily via OpenWeather.Once the user is registered, they have access to the entire API. You can review the document of [Current Weather Data](https://openweathermap.org/current) to access the current weather.

### How to make an API call ###

#### API call: ####

` https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API key} `

#### Parameters: ####

**_lat, lon_**  Geographical coordinates (latitude, longitude). If you need the geocoder to automatic convert city names and zip-codes to geo coordinates and the other way around, use the Geocoding API.

**_Appid_** Your unique API key (you can always find it on your account page under the "API key" tab)

**_Mode_**  Response format. Possible values are xml and html. If you don't use the mode parameter format is JSON by default.

**_Units_**  Units of measurement. standard, metric and imperial units are available. If you do not use the units parameter, standard units will be applied by default.

**_Lang_**  You can use this parameter to get the output in your language.

![Weather App-1](https://user-images.githubusercontent.com/47225405/167269020-a203d632-1c94-4d4d-9a07-5fb4ecbffe84.JPG)
![Weather App-2](https://user-images.githubusercontent.com/47225405/167269067-375fa292-80cc-4b9e-bd87-e636d6420bec.JPG)
