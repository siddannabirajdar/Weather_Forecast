# Weather_Forecast
 A real-time data processing system to monitor weather conditions and provide summarized insights using rollups and aggregates. The system will utilize data from the OpenWeatherMap API (https://openweathermap.org/)

This project fetches real-time weather data for major Indian metros like Delhi, Mumbai, Chennai, Bangalore, Kolkata, and Hyderabad, every 5 minutes (configurable). It processes and stores weather conditions, performs daily rollups, and provides insights like: Average, Maximum, and Minimum Temperatures. Dominant Weather Condition for the day. User-configurable alerts based on threshold breaches (e.g., high temperatures).
Technologies Used:<br>
Frontend: HTML, CSS, JavaScript
API: OpenWeatherMap API<br>
Visualization Libraries: Chart.js (for visualizing trends and alerts)

Setup and Installation: <br>
Prerequisites:<br>
OpenWeatherMap API Key: Sign up for a free API key at OpenWeatherMap.<br>
Web Server: You can use a simple HTTP server like http-server or run directly in your browser.

Instructions<br>

Clone the Repository:<br>
Configure API Key:<br>
Open the script.js file in the root directory.
Replace YOUR_API_KEY with your actual OpenWeatherMap API key:
const API_KEY = 'YOUR_API_KEY';
Run the Project:

You can directly open the index.html file in your browser.
Alternatively, you can start a simple server:
bash
Copy code
npx http-server
Open http://localhost:8080 in your browser.
Usage
The app automatically starts fetching weather data every 5 minutes for the specified locations (Delhi, Mumbai, Chennai, etc.).
You can view daily weather summaries and alerts on the UI.
Alerts are triggered when user-defined thresholds (e.g., temperature above 35°C) are breached.
API Information
OpenWeatherMap API: The system retrieves weather data using the /weather endpoint of OpenWeatherMap for each metro city. The data fetched includes:
main: Main weather condition (e.g., Rain, Clear).
temp: Temperature in Kelvin (converted to Celsius).
feels_like: Perceived temperature in Kelvin.
dt: Timestamp of the update.