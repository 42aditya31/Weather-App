# Weather App 🌦

This is a simple Weather App that fetches real-time weather data using the OpenWeatherMap API. The app provides the current temperature, humidity, wind speed, and weather conditions for any city.

## Features
- Search for weather in any city
- Displays current temperature, humidity, and wind speed
- Updates weather icon based on current conditions (e.g., clouds, rain, clear)

## Project Structure
- **index.html**: The main HTML file, which structures the user interface.
- **style.css**: Contains the styling for the app interface, with a dark theme and centered layout.
- **weather.js**: Contains the JavaScript code to fetch weather data from the API and update the UI accordingly.

## How to Use
1. **Enter a City Name**: Type the name of the city in the input box.
2. **Click the Search Button**: Click on the search button to fetch and display the weather data for the entered city.

## Technologies Used
- HTML5
- CSS3
- JavaScript (Async/Await, Fetch API)

## Setup
1. Clone this repository.
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
2. Navigate to the project directory.
   ```bash
   cd weather-app
   ```
3. Open `index.html` in your browser to view the app.

## API Key
This project uses the OpenWeatherMap API. Make sure to replace the `apiKey` variable in `weather.js` with your own API key.

```javascript
const apiKey = "YOUR_API_KEY";
```


Enjoy using the Weather App! 😊
