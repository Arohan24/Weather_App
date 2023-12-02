
# Weather App

The Weather App is a simple web application that allows users to check the weather conditions and air quality index (AQI) of different cities around the world.

## Features

- **Current Weather**: Displays the current temperature, humidity, wind speed, and weather conditions of the selected city.
- **Air Quality Index (AQI)**: Shows the AQI level of the city based on real-time air quality data.

## Technologies Used

- **React**: The app is built using React, a JavaScript library for building user interfaces.
- **Axios**: Used for making API requests to fetch weather and air quality data.
- **OpenWeatherMap API**: Utilized for fetching weather data based on the city name and geographic coordinates.
- **AQICN API**: Used to fetch real-time air quality data and calculate the AQI.

## Installation

To run the Weather App locally, follow these steps:

1. Clone this repository.
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory.
   ```bash
   cd weather-app
   ```

3. Install dependencies using npm or yarn.
   ```bash
   npm install
   # or
   yarn install
   ```

4. Obtain API keys for OpenWeatherMap and AQICN APIs and replace `<YOUR_OPENWEATHERMAP_API_KEY>` and `<YOUR_AQICN_API_KEY>` respectively in the code.

5. Start the development server.
   ```bash
   npm run dev
   ```

6. Open the app in your browser at `http://localhost:5173`.

## Usage

- Enter the name of the city in the search bar to view the current weather details and AQI of that city.
- Click on the search icon to fetch the weather and AQI data.

## Screenshots

![Weather App Screenshot](/weatherApp_Screenshot.png)

## Contributing

Contributions are welcome! If you find any issues or want to enhance the app, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).