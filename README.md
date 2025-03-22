# Cloud Pulse

## Overview
The Weather Dashboard is a web application that provides users with real-time weather updates and forecasts for various locations. It leverages the OpenWeatherMap API to fetch current weather data and uses Leaflet.js for an interactive map display.

## Features
- **Real-time Weather Updates**: Get the latest weather conditions for any city.
- **Search Functionality**: Enter a city name to retrieve its weather information.
- **Forecast Display**: View weather predictions for the next few days.
- **Interactive Map**: Visualize the selected location on an interactive map.
- **Search History**: Quickly access previously searched locations.

## Technologies Used
- **HTML5**
- **CSS3** (with custom styles)
- **JavaScript (jQuery)**
- **OpenWeatherMap API**
- **Leaflet.js** (for map rendering)
- **Font Awesome** (for icons)
- **Google Fonts** (Lato Font)

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/weather-dashboard.git
   ```
2. Navigate to the project folder:
   ```sh
   cd weather-dashboard
   ```
3. Open `index.html` in your browser.

## Usage
1. Enter a city name in the search box and click the search button.
2. View real-time weather conditions and forecasts for the selected location.
3. Click on different days in the forecast section to see more details.
4. Use the interactive map to explore the selected location visually.

## File Structure
- `index.html` - The main HTML file containing the UI structure.
- `style.css` - Stylesheet for layout and design.
- `app.js` - JavaScript file handling API requests and UI updates.
- `dummy_data.js` - Sample weather data for testing.
- `geoapify_dummy.js` - Sample geolocation data for testing.

## API Configuration
To use this project with real data, you need an OpenWeatherMap API key.
1. Sign up at [OpenWeatherMap](https://openweathermap.org/).
2. Get your API key.
3. Replace the placeholder API key in `app.js`:
   ```js
   var apiKey = 'YOUR_API_KEY';
   ```

## Contribution
Feel free to contribute to this project by submitting pull requests or reporting issues.

## License
This project is open-source and available under the [MIT License](LICENSE).

