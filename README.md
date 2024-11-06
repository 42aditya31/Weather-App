
# Weather App 🌦

A sleek and responsive Weather App that provides real-time weather information for any city, using the [OpenWeatherMap API](https://openweathermap.org/api). Users can quickly access the current temperature, humidity, wind speed, and weather conditions, complete with a dynamic weather icon that reflects the current state (e.g., cloudy, rainy, clear).

## Live Demo
Try the app live: [Weather App](https://42aditya31.github.io/Weather-App/)

## Features
- **City-Based Weather Search**: Enter any city to retrieve up-to-date weather information.
- **Comprehensive Weather Data**: Displays current temperature, humidity, and wind speed.
- **Dynamic Weather Icons**: Icons update based on current conditions to visually represent the weather (e.g., clouds, rain, clear skies).

## Project Structure
- **index.html**: Structures the UI elements for user interaction.
- **style.css**: Styles the app with a dark, centered layout, providing a user-friendly interface.
- **weather.js**: Contains JavaScript code that fetches weather data from the API and dynamically updates the UI.

## Technologies Used
- **HTML5**: Markup for app structure.
- **CSS3**: Styling with a focus on a centered, dark-themed layout.
- **JavaScript (Async/Await, Fetch API)**: Manages API requests and UI updates asynchronously.

## Getting Started

### Prerequisites
- A browser with JavaScript enabled.
- An API key from OpenWeatherMap. Sign up on [OpenWeatherMap](https://openweathermap.org/api) to obtain your key.

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/42aditya31/Weather-App.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Weather-App
   ```
3. Open `index.html` in your browser to view the app locally.

4. Update the `apiKey` variable in `weather.js` with your OpenWeatherMap API key:
   ```javascript
   const apiKey = "YOUR_API_KEY";
   ```

## Usage
1. **Enter a City Name**: Type the city name in the input field.
2. **Click Search**: The app fetches and displays real-time weather data for the specified city.

## Acknowledgments
- **OpenWeatherMap API**: Enables access to accurate, real-time weather data for global locations.
