# Smart Weather Dashboard
A location-based weather app with city search, animated visuals, and performance optimizations using Geolocation, Canvas, Intersection Observer, Network Information, and Background Tasks APIs.

## Features
- **Static Light Background**: Clean, light background (`#f4f7fc`) for a professional and distraction-free appearance.
- **Real-Time Weather**: Displays current weather for the user's location or a searched city, including city name, current time (12-hour format, e.g., 8:30 PM), temperature with rainbow gradient, and weather description.
- **Hourly Forecast**: Shows four hourly forecasts (-2h, -1h, +1h, +2h, e.g., 8:30 PM, 9:30 PM, 11:30 PM, 12:30 AM for 10:30 PM) in 12-hour format with weather-specific icons (sun, cloud, rain, snow, thunderstorm).
- **Interactive Hover Effects**: Smooth hover animations with movement for containers (forecast, forecast-list, current weather, hourly forecast items) and elements (search bar, buttons).
- **Animated Weather Visuals**: Dynamic canvas animations for rain (falling particles), clouds (moving arcs), sun (glowing circle), snow (falling flakes), and thunderstorms (lightning shapes).
- **Lazy-Loaded Forecast**: Hourly forecast loads only when visible using Intersection Observer API.
- **Network-Aware Optimizations**: Adjusts canvas size and particle count for slow networks (e.g., 2G) using Network Information API.
- **Periodic Updates**: Refreshes weather data in the background during idle times with Background Tasks API.
- **Location Refresh**: "Use My Location" button to fetch weather based on current geolocation.
- **Unit Toggle**: Switch between Celsius and Fahrenheit with a toggle button.

## Deployment
Hosted on GitHub Pages: https://prudhvi1519.github.io/smart-weather-dashboard/

## Setup
1. Clone the repository.
2. Replace the OpenWeatherMap API key in `index.html` with your own from openweathermap.org.
3. Open `index.html` in a browser or deploy via GitHub Pages.
