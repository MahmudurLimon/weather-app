🌦️ Weather App

A simple and elegant React-based Weather Application that allows users to search for real-time weather data for any city using the OpenWeatherMap API.
Live Demo 👉 https://mahmudurlimon.github.io/weather-app/

🚀 Features
  -> 🌍 Search weather by city name
  -> 🌡️ Displays temperature, humidity, wind speed & real-time weather conditions
  -> 🎨 Clean UI with background image & smooth layout
  -> ⚡ Built with React + Axios
  -> 📱 Responsive design
  -> 🛠️ Technologies Used
        React.js

Axios

OpenWeatherMap API

CSS (Custom Styling)

📸 Screenshot

(You can add an image here — optional)
Example:

![Weather App Screenshot](./assets/screenshot.png)

⚙️ How It Works

The user enters a city name in the input box.

When pressing Enter, the app sends a request to:

https://api.openweathermap.org/data/2.5/weather?q={city}&units=imperial&appid=YOUR_API_KEY


The API returns weather info such as:

Temperature (°F)

Weather condition

Feels Like temperature

Humidity

Wind speed

Data is displayed dynamically on the UI.

📦 Installation & Setup

Clone this repository:

git clone https://github.com/mahmudurlimon/weather-app.git


Install dependencies:

npm install


Run the project locally:

npm start


To build for production:

npm run build

🔑 API Key Setup

Replace the appid in the URL inside App.js:

const url = `https://api.openweathermap.org/data/2.5/weather?q=${location}&units=imperial&appid=YOUR_API_KEY`


Get your API key for free at:
👉 https://openweathermap.org/api

📁 Project Structure
weather-app/
│
├── public/
├── src/
│   ├── assets/
│   │   └── weather.jpg
│   ├── App.js
│   ├── index.js
│   └── index.css
│
└── README.md

🌐 Deployment

This project is deployed using GitHub Pages.
To deploy:

npm run build
npm run deploy


Make sure homepage is set in package.json:

"homepage": "https://mahmudurlimon.github.io/weather-app"

📜 License

This project is open-source and available under the MIT License.
