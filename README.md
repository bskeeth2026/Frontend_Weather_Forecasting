# ☀️ Weather Forecasting Web App

##  Overview

This **Weather Forecasting Web App** delivers real-time and 7-day forecast data using the **OpenWeatherMap API**. It features a clean, responsive user interface built with **HTML**, **CSS**, and **JavaScript**, enabling users to check current weather conditions and upcoming forecasts for any location.

---

##  Features

* Real-time weather updates
* 7-day weather forecast
* Displays:

  * Temperature
  * Humidity
  * Atmospheric pressure
  * Wind speed
  * Weather condition icons
  * Sunrise & sunset times
* Location input or geolocation support
* Responsive and user-friendly interface

---

##  Tech Stack

###  Frontend (HTML, CSS, JavaScript)

* **User Interface**

  * Shows current date and time
  * Weather icons and condition summaries
  * Displays weather stats: temperature, humidity, pressure, wind speed
* **User Interaction**

  * Allows manual location input or automatic geolocation
  * Sends location data to backend to retrieve weather info

###  Backend (JavaScript + OpenWeatherMap API)

* **API Integration**

  * Fetches real-time weather and forecast data from OpenWeatherMap using your API key
* **Data Processing**

  * Parses JSON responses
  * Extracts weather details: temp, humidity, wind speed, etc.
* **Weekly Forecast Support**

  * Retrieves daily forecast data for the upcoming week
* **Data Delivery**

  * Sends clean, processed data to frontend for display

---

##  Workflow

1. User enters a location or enables geolocation.
2. Frontend sends location data to the backend.
3. Backend uses the OpenWeatherMap API to request weather data.
4. API returns weather data in JSON format.
5. Backend extracts relevant data.
6. Processed data is sent back to the frontend.
7. Frontend updates the UI with current and weekly weather details.

---

##  Requirements

* A valid OpenWeatherMap API Key
* Web browser with JavaScript enabled
* Internet connection

---

##  Future Enhancements

* Add weather alerts or warnings
* Local storage for recent search history
* Dark mode toggle
* Multi-language support

---

## ⚠️ Disclaimer

This application is for educational and demonstration purposes. Weather data accuracy depends on the OpenWeatherMap service.

---

Stay updated, rain or shine! ☔️️☀️
