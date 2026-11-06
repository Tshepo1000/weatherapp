# Weather App

A small web app that shows real-time weather for any city. Type a city name and the app fetches the current conditions from the OpenWeatherMap API and displays them on the page.

## Features

- Search by city name
- Current weather conditions fetched live from the OpenWeatherMap API
- Single-page HTML, CSS and JavaScript app with no build step

## Getting started

1. Clone the repository:

   ```bash
   git clone https://github.com/Tshepo1000/weatherapp.git
   cd weatherapp
   ```

2. Create a free API key at [openweathermap.org](https://openweathermap.org/api).
3. Open `index.html` and set your own key where the API request is made.
4. Open `index.html` in your browser and search for a city.

> **Security note:** API keys placed in front-end code are visible to anyone who opens the page. Use a free key with usage limits, never commit a key you want to keep private, and rotate the key if it is exposed. A future version should call the API through a small backend proxy.

## Tech stack

- HTML5, CSS3, JavaScript (Fetch API)
- [OpenWeatherMap](https://openweathermap.org/) current weather API

## Status and roadmap

The core search-and-display feature works. Planned improvements:

- [ ] Move the API key out of the front-end code
- [ ] Add friendly error messages for unknown cities and network failures
- [ ] Add a 5-day forecast and unit toggle (°C / °F)

## Author

Tshepo Sekete, [GitHub](https://github.com/Tshepo1000)
