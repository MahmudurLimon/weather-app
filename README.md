# 🌦️ Weather App

A simple and elegant **React-based Weather Application** that allows users to search real-time weather data for any city using the **OpenWeatherMap API**.

🔗 **Live Demo:**  
https://mahmudurlimon.github.io/weather-app/

---

## 🚀 Features

- 🔍 Search weather by city name  
- 🌡️ Real-time temperature (°F)  
- 🌥️ Displays weather condition  
- 💨 Wind speed & 🌫️ humidity  
- 📱 Responsive & clean UI  
- ⚡ Powered by React + Axios  

---

## 🛠️ Technologies Used

- **React.js**
- **Axios**
- **OpenWeatherMap API**
- **CSS (Custom Styling)**

---

## ⚙️ How It Works

1. User types a city name and presses **Enter**  
2. App sends an API request to:  https://api.openweathermap.org/data/2.5/weather?q={city}&units=imperial&appid=YOUR_API_KEY
3. The API returns:  
- Temperature  
- Feels Like  
- Humidity  
- Wind Speed  
- Weather Description  
4. The UI updates instantly using React state.

---

## 📦 Installation & Setup

Clone the repository:

```bash
git clone https://github.com/mahmudurlimon/weather-app.git
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

Build for production:

```bash
npm run build
```

## 🔑 API Key Setup

Inside App.js, replace:

```bash
const url = `https://api.openweathermap.org/data/2.5/weather?q=${location}&units=imperial&appid=YOUR_API_KEY`
```

Get your free API key from:
https://openweathermap.org/api

## 📁 Project Structure

```bash
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
```

## 🌐 Deployment (GitHub Pages)

Add this to package.json:

```bash
"homepage": "[your-project-page]"
```

Deploy with:

```bash
npm run build
npm run deploy
```

## 🏷️ License
This project is open-source under the MIT License.
