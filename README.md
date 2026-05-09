# Weather Card

Weather Card is a React weather planning dashboard for checking live city conditions, hourly weather, five-day forecasts, saved places, and practical planning notes.

## Live Demo

Live link coming soon.

## Why This Project

This project follows the feature patterns of successful weather apps: quick city search, saved locations, current conditions, hourly outlooks, daily forecasts, weather warnings, and practical notes that help users plan their day.

## Key Features

- Search live weather by city using Open-Meteo data
- View current temperature, condition, feels-like temperature, humidity, rain chance, and wind
- See an hourly forecast strip for quick day planning
- View a five-day forecast with highs, lows, condition, and rain probability
- Toggle between Fahrenheit and Celsius
- Save favorite cities in local storage
- Reopen recent searches quickly
- Show visual weather indicators for clear, cloudy, rain, snow, sleet, and storms
- Display condition warnings for rain, wind, heat, and freezing temperatures
- Generate practical planning notes based on temperature, rain, and wind
- Responsive dashboard layout for desktop and mobile

## User Workflow

1. Search for a city.
2. Review current conditions and the planning note.
3. Check the hourly strip for short-term weather changes.
4. Compare the five-day forecast before saving a city for later.

## Tech Stack

- React
- Vite
- CSS
- Open-Meteo Geocoding API
- Open-Meteo Forecast API
- Local Storage

## What I Practiced

- Fetching and transforming API data
- Async loading and error states
- Derived weather messages
- Unit toggles
- Saved and recent location state
- Responsive dashboard layout
- Visual condition indicators

## Run Locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```
