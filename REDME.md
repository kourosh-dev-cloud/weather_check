# 🌤 Weather Checker with Python and WeatherAPI

This project allows you to check real-time weather information for any city using the [WeatherAPI](https://www.weatherapi.com/).  
It fetches temperature and weather conditions using the city name entered by the user.

## 🚀 Features

- Get live weather info (temperature, condition, city, and country)
- Based on user's input (city name)
- Uses public REST API (weatherapi.com)
- Written in simple Python, easy to read and modify

## 📦 Requirements

- Python 3.x
- requests library (install with: pip install requests)

## 🧠 How It Works

1. User enters the name of a city (e.g., Tehran)
2. The script sends a request to WeatherAPI with your API key
3. It prints the temperature and weather condition in real-time

## 🔐 API Key

You need an API key from [weatherapi.com](https://www.weatherapi.com/).  
Register for a free account and replace your_api_key_here in the script with your own key.

```python
api_key = "your_api_key_here"

💻Example Output

📍 City: Tehran
🌍 Country: Iran
🌡 Temperature: 31.0 °C
🌤 Condition: Sunny

📂Project Structure

weather-api/
├── weather_api.ipynb       # Main notebook file
├── README.md               # This file

✍ Author

Created by Kourosh
GitHub: @kourosh-dev-cloud