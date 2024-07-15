
# EurOrbit - European Weather Forecast

EurOrbit is a web application that provides weather forecasts for various European cities. This project was created as part of the Coursera course "Build a Website using an API with HTML, JavaScript, and JSON" by Coursera Project Network.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Introduction
EurOrbit utilizes the 7Timer API to fetch and display weather forecasts for selected locations. Users can select a city from a dropdown menu, and the application will display the weather forecast for the next seven days, including weather icons and temperature details.

## Features
- Select a city to view its weather forecast
- Displays weather conditions with icons
- Provides temperature highs and lows for each day
- Responsive design suitable for various devices

## Technologies Used
- HTML
- CSS
- JavaScript (with async/await for asynchronous operations)
- 7Timer API for weather data
- Fetch API for making HTTP requests

## Setup
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/coderooz/eurorbit-weather-forecast.git
    ```

2. Navigate to the project directory:
    ```bash
    cd eurorbit-weather-forecast
    ```

3. Ensure you have the `city_coordinates.csv` file in the project directory with the following structure (without headers):
    ```csv
    lat,lon,city,country
    52.5200,13.4050,Berlin,Germany
    48.8566,2.3522,Paris,France
    ```

4. Ensure you have the necessary weather icons in an `icons` folder in the project directory. The icons should be named according to the weather conditions (e.g., `clear.png`, `partly-cloudy.png`).

5. Open `index.html` in your web browser.

## Usage
1. Open the `index.html` file in your web browser.
2. Select a location from the dropdown menu.
3. View the weather forecast for the selected city.

## Project Structure
```
eurorbit-weather-forecast/
├── css/
│   └── style.css
├── icons/
│   ├── clear.png
│   ├── cloudy.png
│   ├── light-rain.png
│   └── ... (other weather icons)
├── js/
│   └── main.js
├── city_coordinates.csv
├── index.html
└── README.md
```

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

```

## Acknowledgments
- Coursera Project Network for providing the course and guidance.
- 7Timer API for weather data.

## Author
- Ranit Saha:Coderooz (viewersweb02@gmail.com)

```
