# 🌦️ Async Weather Tracker

Async Weather Tracker is a simple web application that allows users to search for weather information of any city using the **OpenWeatherMap API**. It demonstrates the use of **async/await**, **fetch API**, and **localStorage** to manage search history.

---

## 🚀 Features
- Search weather by city name.
- Displays:
  - City name
  - Temperature (°C)
  - Humidity (%)
  - Wind speed (m/s)
- Maintains search history using **localStorage**.
- Clickable history buttons to quickly re-fetch weather data.
- Event loop logs to visualize async execution flow.

---

## 🛠️ Technologies Used
- **HTML5** for structure
- **CSS3** for styling
- **JavaScript (ES6+)** for logic
- **OpenWeatherMap API** for weather data

---

## ⚙️ Setup Instructions
1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Replace the placeholder API key in the script with your own:
   ```javascript
   const API_KEY = "YOUR_API_KEY_HERE";

---

## 🖥️ Usage
- Enter a city name in the search bar and click search.
- Weather details will be displayed in the Weather Info section.
- Each searched city is saved in localStorage and shown in the Search History section.
- Click on a history button to quickly view that city’s weather again.
- Event loop logs show the async execution steps for better understanding.
