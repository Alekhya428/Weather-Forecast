# 🌦️ Weather Forecast

A simple and responsive Weather Forecast web application that allows users to search for a city and view its current weather information.

## 📌 Project Description

The Weather Forecast application allows users to enter a city name and get real-time weather information.

The application uses a JavaScript frontend and a Node.js/Express backend. The backend communicates with the OpenWeatherMap API to retrieve weather data and sends the required information back to the frontend.

## ✨ Features

- Search weather by city name
- Displays current temperature
- Displays humidity
- Displays weather description
- Displays a weather emoji based on weather conditions
- Handles invalid city names
- Displays an error when no city is entered
- Uses a backend API to securely handle the OpenWeatherMap API key
- Responsive and simple user interface

## 🛠️ Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js

### API
- OpenWeatherMap API

### Other Tools
- Git
- GitHub
- dotenv
- CORS

## 🔄 How the Project Works

1. The user enters a city name in the search box.
2. JavaScript sends a request to the Express backend.
3. The backend receives the city name.
4. The backend sends a request to the OpenWeatherMap API.
5. OpenWeatherMap returns the weather data.
6. The backend sends the data back to the frontend.
7. JavaScript displays the temperature, humidity, description, and weather emoji.

## 📂 Project Structure

```text
Weather/
│
├── .gitignore
├── README.md
│
├── Backend/
│   ├── .env
│   ├── package.json
│   ├── package-lock.json
│   └── server.js
│
└── Frontend/
    ├── index.html
    ├── index.js
    └── styles.css