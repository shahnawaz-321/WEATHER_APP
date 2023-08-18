# WEATHER_APP
#city serach section: the "search" section contains an input you can enter the name of a city 
.next to the input box,there is a search button with an image icon
#weather information section:the "weather "section display the weather details
..an image icon represents the current weather condition like rain or clouds
..the temprature is shown in Celsius,the city's name is displayed,and there's subsection for additional weather details.
#FETCHING AND DISPLAYING WEATHER DATA(JAVASCRIPTS):
the javascript code section handles the dynamic part of the webpage
.it defines important constants like the API key and the URL to fetch weather data.
it also selects various HTML elements (like the search input,button,and weather icon)that will be updated
#FETCHING WEATHER DATA FUNCTIONS:
*there is an asynchronous function named 'checkweather'that takes the name of a city as a parameter
*it fetches weather data from the API based on the city name and API KEY
* the fetched data is converted to a usable format (JSON) and stored in the 'data' variables
* UPDATING WEATHER INFORMATION:the function then updates varios HTML elements with the data from the API response
* .city name,temperature,humidity,and wind speed are updated accordingly
* #WEATHER ICON SELECTION:depending on the weather condition provided in the API data,the weather icon is updated
* #differents images are used for different condition (clouds,clear sky,rain,mist,drizzles)
* #USER INTERACTIONS:an events listner is added to the search button
* #when the button is clicked ,it triggers the 'checkweather' function with the city name entered in the search input
* 
