# 🌦️ Weather Forecast Web Application

An interactive, responsive web application for viewing current weather, hourly updates, and 5-day forecasts using real-time data.
The project focuses on clean UI, accurate weather visualization, and a smooth user experience.
---
## 🚀 Features

### 🌍 Location-Based Weather
- Fetch weather using current location (Geolocation API)
- Default fallback location (New Delhi) if permission is denied
- Manual city search support

### ⏱️ Forecast Details
---
- Current weather (temperature, condition, wind, humidity)
- Hourly forecast (next 24 hours)
- 5-day weather forecast
- Weather icons fetched dynamically from OpenWeatherMap

### 📊 Weather Metrics
---
- Temperature (°C)
- Wind speed (Km/h) with direction visualization
- Weather description & icons
- Day-wise max temperature

### 🎨 UI / UX
---
- Clean, modern layout
- SVG-based icons and visuals
- Smooth slider for hourly forecast
- Responsive design (desktop & mobile)
- Accessible labels (aria-*)

### 🌙 Theme Support
---
- Dark / Light mode toggle
- Theme preference stored in localStorage
- Global theme applied using body class

### 🧠 Why this project?
---
Weather applications are a great way to combine:
- API handling
- Asynchronous data fetching
- Real-world data visualization
- React hooks and context
This project helps understand how frontend applications interact with external APIs, manage global state, and present dynamic data cleanly.

### 🛠️ Tech Stack
---
- Frontend: React (Vite)
- Styling: CSS Modules
- State Management: React Context API
- APIs: OpenWeatherMap API
- Language: JavaScript (ES6+)
- Browser APIs: Geolocation API, LocalStorage

## 📂 Project Structure
src/
├── components/
│   ├── Today.jsx
│   ├── Forecast.jsx
│   ├── Header.jsx
│   └── Search.jsx
│
├── context/
│   └── AppContext.jsx
│
├── hooks/
│   ├── UseCurrentLocation.js
│   └── UseToggleTheme.js
│
├── assets/
│   ├── windSpeed.png
│   └── icons/
│
├── App.jsx
└── main.jsx

## ▶️ Running the Project Locally

1️⃣ Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git

2️⃣ Install dependencies
npm install

3️⃣ Start the development server
npm run dev

4️⃣ Open in browser
http://localhost:5173

## 📊 How to Use

- Allow location access for automatic weather detection
- Or search for a city manually
- View:
  - Current weather conditions
  - Hourly forecast slider
  - 5-day forecast cards
- Toggle Dark / Light mode anytime
- Refresh or revisit — preferences persist
