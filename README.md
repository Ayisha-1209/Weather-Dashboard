# Weather Dashboard Application

This project is a simple, responsive weather dashboard application developed using HTML, CSS, jQuery, and AJAX. The application displays real-time weather information for a user-selected city using data fetched from the OpenWeatherMap API.

## Overview

The Weather Dashboard Application is designed to provide users with current weather conditions for any city they search for. The app fetches data from the OpenWeatherMap API and displays key weather details such as temperature, humidity, wind speed, and weather conditions.

## Features

- **Search Functionality:** Users can search for a city to get its current weather information.
- **Real-time Weather Data:** The app displays current weather details including temperature, humidity, wind speed, and weather description.
- **Responsive Design:** The layout is fully responsive, ensuring compatibility across various devices and screen sizes.
- **Error Handling:** The application handles errors for scenarios like invalid city input or API fetch failures, providing appropriate feedback to the user.

## Technologies Used

- **HTML5:** Structure of the application.
- **CSS3:** Styling and layout.
- **jQuery:** DOM manipulation and state management.
- **AJAX:** Fetching data from the OpenWeatherMap API.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-dashboard.git

2. Navigate to the project directory:

   ```bash
   cd weather-dashboard
   
3. Open the index.html file in your browser to view the application.

## API Integration

This application uses the OpenWeatherMap API to fetch weather data. You'll need to obtain a free API key from OpenWeatherMap and replace {API key} in the API endpoint with your key.

Example API call:

 ```bash
 GET http://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}

