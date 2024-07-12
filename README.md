# Weather Forecast Project
## Overview
**This project is a Python-based weather forecast application that retrieves and displays current weather conditions and forecasts for a given location. The application uses the OpenWeatherMap API to fetch weather data and provides a user-friendly interface to display the information.**

Features
Retrieves current weather conditions, including temperature, humidity, wind speed, and weather description
Displays 5-day weather forecast with high and low temperatures, weather description, and icons
Supports multiple locations, allowing users to switch between different cities
Provides a simple and intuitive user interface using a command-line interface (CLI)
Requirements
Python 3.8 or later
OpenWeatherMap API key (free registration required)
requests library for making API calls
json library for parsing JSON data
Installation
Clone the repository: git clone https://github.com/your-username/weather-forecast.git
Install the required libraries: pip install requests json
Create a file named api_key.txt in the project root directory and add your OpenWeatherMap API key
Run the application: python weather_forecast.py
Usage
Run the application: python weather_forecast.py
Enter a location (city name or zip code) when prompted
View the current weather conditions and 5-day forecast
Example Output

Verify

Open In Editor
Edit
Copy code
Welcome to the Weather Forecast App!

Enter a location (city name or zip code): New York
Current Weather:
  Temperature: 22°C (72°F)
  Humidity: 60%
  Wind Speed: 15 km/h (9 mph)
  Weather Description: Partly Cloudy

5-Day Forecast:
  Day 1:
    High: 25°C (77°F)
    Low: 18°C (64°F)
    Weather Description: Sunny
  Day 2:
    High: 28°C (82°F)
    Low: 20°C (68°F)
    Weather Description: Partly Cloudy
  ...
License
This project is licensed under the MIT License. See LICENSE for details.

Contributing
Contributions are welcome! If you'd like to add new features or improve the existing code, please submit a pull request.

Author
[Your Name]

Acknowledgments
OpenWeatherMap API for providing weather data
Python community for creating and maintaining the requests and json libraries
