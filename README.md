#  Weather App

A simple and responsive weather web application that uses **OpenWeatherMap API** and **IP geolocation** to fetch and display real-time weather data for the user's current location. Users can toggle between **Celsius** and **Fahrenheit** views.

---

## 🌐 Features

- 🌍 Automatically detects user location via IP (using `ipapi.co`)
- 🌡️ Displays current temperature in Celsius or Fahrenheit
- ⛅ Shows weather conditions, humidity, pressure, and wind speed
- 📍 Displays location coordinates (latitude and longitude)
- 🔁 Toggle button for switching between Celsius and Fahrenheit
- 🎨 Stylish and responsive UI built with **HTML, CSS Grid, and custom fonts**

---

## 🛠️ Technologies Used

- HTML5 / CSS3 (with Google Fonts)
- JavaScript (jQuery)
- OpenWeatherMap API
- ipapi.co (for user location)
- Weather icons via OpenWeatherMap

---

## 🚀 How It Works

1. Gets the user’s IP-based geolocation using `https://ipapi.co/json/`
2. Fetches weather data using the OpenWeatherMap API and the acquired lat/lon
3. Displays:
   - Current temperature
   - Max/Min temperatures
   - Weather description and icon
   - Pressure, Humidity, Wind speed
4. Allows toggling between Celsius and Fahrenheit via UI buttons

---

## 📦 Setup Instructions

1. Replace the API key in the script:
   ```javascript
   https://api.openweathermap.org/data/2.5/weather?...&appid=YOUR_API_KEY
2. Open the HTML file in a browser to test locally.
