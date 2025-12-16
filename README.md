#  WeatherApp

A responsive weather application built using **Vite + React + Material UI** that allows users to search for the current weather information of any city in the world.

This project fetches live weather data from the **OpenWeatherMap API** and displays it in a clean and user-friendly layout with dynamic visuals based on weather conditions.

---

##  Features

 **Search Functionality:** Search weather by specific city name.  
 **Detailed Metrics:** Displays:
-  Current Temperature
-  Humidity
-  Min & Max Temperature
-  "Feels Like" Temperature
-  Weather description (e.g., haze, clear sky)  
 **Dynamic UI:**
- Changes background images (Hot , Cold , Rain ) based on temperature and humidity.
- Displays contextual icons (Sun, Snowflake, Thunderstorm) depending on the weather.
 **Error Handling:** Gracefully handles invalid city names with user feedback.
 **Clean Design:** Built with **Material UI** components (Cards, TextFields, Buttons).
 **Performance:** Powered by **Vite** for fast development and optimized builds.

---

##  Tech Stack

- **Frontend:** [React](https://react.dev/), [Vite](https://vitejs.dev/)
- **Styling & Components:** [Material UI (MUI)](https://mui.com/), [Emotion](https://emotion.sh/)
- **Icons:** MUI Icons Material
- **API:** [OpenWeatherMap API](https://openweathermap.org/api)

---

## Folder Structure

```bash
WeatherApp/
├── public/
│   └── vite.svg              # Vite Logo
├── src/
│   ├── assets/
│   │   └── react.svg         # React Logo
│   ├── components/           # Reusable UI Components
│   │   ├── InfoBox.css       # Styles for InfoBox
│   │   ├── InfoBox.jsx       # Displays weather details & dynamic images
│   │   ├── SearchBox.css     # Styles for SearchBox
│   │   ├── SearchBox.jsx     # Handles search input & API calls
│   │   └── WeatherApp.jsx    # Main container component managing state
│   ├── App.css               # Global app styles
│   ├── App.jsx               # Root component
│   ├── index.css             # Base CSS reset
│   └── main.jsx              # Application entry point
├── .gitignore
├── eslint.config.js          # ESLint configuration
├── index.html                # HTML entry point
├── package.json              # Dependencies and scripts
└── vite.config.js            # Vite configuration