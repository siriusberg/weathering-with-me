# ⛅ Weathering With Me
A weather app built using React and the OpenWeatherMap API to display current weather conditions and forecasts for various cities.

## 📑 Table of Contents
- [Description](description)
- [Preview](preview)
- [Features](features)
- [Installation](installation)
- [Usage](usage)
- [API Configuration](api-configuration)
- [Technologies Used](technologies-used)
- [Contributing](contributing)

## ¶ Description
The Weather App is a React-based web application that allows users to search for cities and view the current weather conditions as well as the daily forecast for the upcoming days. The app utilizes two main APIs: the OpenWeatherMap API to fetch weather data and the GeoDB Cities API from RapidAPI to provide autocomplete suggestions for city names.

## 📷 Preview
<img src="./public/Preview/Screenshot (57).png">

## ⭐️ Features
- Search for cities and retrieve weather data.
- Display current weather conditions including temperature, description, and icon.
- Display a daily forecast for the upcoming days with details like temperature, pressure, humidity, wind speed, and more.
- Utilize the GeoDB Cities API for city name autocomplete suggestions.

## &#x1F527; Installation
1. Clone the repository: `git clone https://github.com/siriusberg/weathering-with-me.git`
2. Navigate to the project directory: `cd weather-app`
3. Install the required dependencies: `npm install` <br>
   (<b>PS</b>: You can use `npm install --force` if the dependencies is outdated and then update it manually)

## 🖱️ Usage
1. Obtain your API keys:
    - Sign up for an API key from the [OpenWeatherMap API](https://openweathermap.org/api)
    - Register for an account on [RapidAPI](https://rapidapi.com) and subscribe to the [GeoDB Cities API](https://rapidapi.com/wirefreethought/api/geodb-cities).
2. Replace `WEATHER_API_KEY` in `src/components/api.js` with your OpenWeatherMap API key.
3. Replace `X-RapidAPI-Key` in `src/components/api.js` with your RapidAPI key.
4. Start the development server: `npm start`
5. Open your web browser and go to `http://localhost:3000` to use the app.

## 🛠 API Configuration 
  ### OpenWeatherMap API
  To use  the OpenWeatherMap API, follow these steps:
  1. Visit [OpenWeatherMap](https://openweathermap.org/) and create an account.
  2. Generate an API key from your account settings.
  3. Replace `WEATHER_API_KEY` in `src/components/api.js` with your API key.

  ### GeoDB Cities API
  To use the GeoDB Cities API from RapidAPI, follow these steps:
  1. Register for an account on [RapidAPI](https://rapidapi.com).
  2. Subscribe to the [GeoDB Cities API](https://rapidapi.com/wirefreethought/api/geodb-cities).
  3. Replace `X-RapidAPI-Key` in `src/components/api.js` with your RapidAPI key.

## 💻 Technologies Used
- [React](https://react.dev/)
- [react-select-async-paginate](https://github.com/vtaits/react-select-async-paginate/tree/master/packages/react-select-async-paginate)
- [react-accessible-accordion](https://github.com/springload/react-accessible-accordion)
- [RapidAPI](https://rapidapi.com) and [OpenWeatherMap](https://openweathermap.org/)

## 👤 Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to create an issue or submit a pull request.


