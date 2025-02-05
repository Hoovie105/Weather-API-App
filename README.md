# Weather API App

## Description

The Weather API App is a simple weather application built using Python and PyQt5. It fetches real-time weather data from the 
OpenWeatherMap API and displays the current temperature, weather description, and an appropriate emoji 
representation of the weather conditions.

## Features

- User-friendly GUI built with PyQt5
- Fetches real-time weather data from OpenWeatherMap API
- Displays temperature in Celsius
- Shows weather condition description
- Uses weather-related emojis for easy visual representation
- Error handling for common API and network issues

## Technologies Used

- Python
- PyQt5 for the graphical interface
- Requests library for API communication

## Installation

1. Clone the repository:
   git clone https://github.com/yourusername/weather-api-app.git

2. Navigate to the project folder:
   cd weather-api-app

3. Install dependencies:
   pip install PyQt5
   pip install requests

4. Run the application:
   python weather_app.py

## Configuration

Replace `api_key` in `get_weather` function with your OpenWeatherMap API key:
api_key = "your_api_key_here"

## Usage

1. Launch the application.
2. Enter a city name in the input field.
3. Click the "Get Weather" button to fetch and display the weather details.

## Error Handling

The application includes error handling for cases such as:

- Invalid city name
- API key errors
- Connection issues

## License

This project is open-source and available under the MIT License.

## Author

Hoovie105 - https://github.com/Hoovie105/
