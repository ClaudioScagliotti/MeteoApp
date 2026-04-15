# MeteoApp
Little exercise used to try new AI tools

📌 Description

Weather App is a web application that allows users to check current weather conditions and future forecasts for any city in the world.
The app uses the free Open-Meteo APIs to retrieve up-to-date data and displays it through a modern, clean, and interactive interface.

🚀 Main Features
🔍 City search with real-time suggestions
🌡️ Current temperature and “feels like” temperature
🌤️ Weather description with intuitive icons
💨 Detailed data:
Wind speed
Humidity
Visibility
Atmospheric pressure
🕒 Hourly forecast (next 24 hours)
📅 Daily forecast (today + next 3 days)
🌍 City geographic coordinates
⚙️ Unit toggle (°C / °F)
❗ Error handling (city not found, API issues)
⏳ Loading indicator
🖼️ Interface Preview
Main screens:
City input
Current weather display
Hourly forecast
Daily forecast
🛠️ Technologies Used
HTML5
CSS3 (modern + responsive design)
JavaScript (Vanilla)
Open-Meteo API
Geocoding API
Weather Forecast API
📡 How It Works
The user enters a city name
The app uses the Geocoding API to retrieve:
City name
Coordinates (latitude, longitude)
The coordinates are used to call the Weather API
The retrieved data is processed and displayed in the UI
⚙️ Installation & Usage
1. Clone the project
git clone https://github.com/your-username/weather-app.git
2. Open the project

Open the file:

index.html

or simply double-click the HTML file.

👉 No dependencies or server setup required.

📂 Project Structure
/weather-app
│── index.html
│── README.md

All code (HTML, CSS, and JavaScript) is contained in a single file for simplicity.

🧠 Core Logic
search() → handles city search
fetchWeather() → retrieves weather data
renderWeather() → updates the UI
fetchSuggestions() → dynamic suggestions
renderDaily() → daily forecast rendering
🧪 Testing

The app includes a built-in test mode that can be activated with:

?test=1

Example:

index.html?test=1

This mode tests:

Core functions
UI rendering
API data handling
🤖 Use of Artificial Intelligence

AI was used to:

Structure the code
Improve readability
Optimize API handling
Implement advanced features

All generated code was reviewed and fully understood before being used.

📈 Possible Improvements
📱 Better mobile optimization
⭐ Save favorite cities
📍 Automatic geolocation
🎨 UI/UX improvements and animations
🔔 Weather notifications
📄 License

This project is open-source and free to use for educational purposes.
