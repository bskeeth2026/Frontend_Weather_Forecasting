# Frontend_Weather_Forecasting
This weather app leverages the power of the OpenWeatherMap API to
bring you real-time and next-week forecasts directly to your screen.
Here’s a peek under the hood:

Frontend(HTML,CSS,JavaScript):
● User Interface: Creates a visually appealing layout displaying
current date and time,weather icons, and numerical values for
humidity,pressure and wind speed.
● User Interaction: Handles user input(like location selection) and
interacts with the backend to fetch weather data.

Backend(JavaScript with OpenWeatherMap API):
● API Integration: Makes requests to the OpenWeatherMap API
using your unique API key, specifying your desired location.
● Data Processing: Parses the JSON response from the API,
extracting relevant weather data like temperature,
humidity,pressure,wind speed,sunrise and sunset times.
● Data Delivery: Provides the processed weather data to the
frontend for display.
● Weekly Forecast: Fetches data for the next few days, enabling
the app to showcase a future look at the weather.

Putting it Together:
1.User enters a location or uses geolocation.
2.Frontend sends the location data to the backend.
3.Backend calls the OpenWeatherMap API with the location.
4.API returns weather data in JSON format.
5.Backend processes the JSON data and extracts relevant information.
6.Backend sends the processes data back to the frontend.
7.Frontend updates the UI with the received weather data.
