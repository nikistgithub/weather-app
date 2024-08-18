# React Weather App 

## Overview

The Weather App is a React-based application that provides current weather information for any city. It fetches data from the OpenWeatherMap API and displays it with dynamic styling, including images and backgrounds that reflect the weather conditions.

## Features

- Dynamic Weather Display: Shows the current weather, temperature, humidity, and wind speed for a selected location.
- Location Search: Allows users to search for the weather in different cities.
- Responsive Design: The interface is designed to adapt to various screen sizes.
- Real-Time Data: Fetches and displays up-to-date weather information from OpenWeatherMap.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. **Navigate to the Project Directory**:

    ```bash
    cd weather-app
    ```

3. **Install the Dependencies**:

    ```bash
    npm install
    ```

4. **Start the Development Server**:

    ```bash
    npm run dev
    ```

5. **Open Your Browser**:

    Navigate to [http://localhost:5173](http://localhost:5173) to view the app.

## Usage

- Default Location: On initial load, the app displays the weather for London.
- Search for a City: Enter the city name in the search bar and press "Enter" or click the search icon to view the weather for that location.
- View Weather Information: The app displays the temperature, weather condition, humidity, and wind speed.

## API Integration

The app uses the OpenWeatherMap API to fetch weather data. You need an API key to use this service.

- API Key: The app requires an API key, which can be obtained from the [OpenWeatherMap website](https://openweathermap.org/appid).

- API Endpoint:

```bash
https://api.openweathermap.org/data/2.5/weather?q={city_name}&units=Metric&appid={api_key}
```
## Acknowledgements

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/).
- Icons and images are used under appropriate licenses.
