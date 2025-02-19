Weather App

A simple PyQt5-based Weather App that fetches real-time weather data using the OpenWeatherMap API.

Features

  Enter a city name to get the current weather.

  Displays temperature in Celsius.

  Provides an appropriate weather emoji.

  Shows a brief weather description.

  Handles API errors and displays user-friendly messages.

Prerequisites

Make sure you have Python installed (Python 3 recommended). You will also need to install the required dependencies.

Installation

Clone the repository:

git clone https://github.com/your-username/weather-app.git
cd weather-app

Install dependencies:

    pip install -r requirements.txt

Run the application:

    python weather_app.py

Dependencies

    PyQt5
    
    requests
    
    Install using:
    
    pip install PyQt5 requests
    
    API Key Setup
    
    This app uses OpenWeatherMap API. Get your free API key from OpenWeatherMap and replace the api_key variable in weather_app.py:
    
    api_key = "your_api_key_here"

Usage

    Run the script.
    
    Enter a city name.
    
    Click "Get Weather".
    
    View the temperature, weather condition, and an appropriate emoji.
    
    Error Handling
    
    Displays error messages for invalid cities.
    
    Shows connection errors in case of network failure.
    
    Handles API-related issues (e.g., invalid API key).

License

This project is licensed under the MIT License.

Contributing

Feel free to fork and contribute! Open an issue or pull request for discussions.

Author

SWAROOP BHATTACHARYA - GITHUB PROFILE-kingjames-code

