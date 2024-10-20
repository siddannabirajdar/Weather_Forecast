# Weather_Forecast
 A real-time data processing system to monitor weather conditions and provide summarized insights using rollups and aggregates. The system will utilize data from the OpenWeatherMap API (https://openweathermap.org/)

<<<<<<< HEAD >>>>>>>>
This project fetches real-time weather data for major Indian metros like Delhi, Mumbai, Chennai, Bangalore, Kolkata, and Hyderabad, every 5 minutes (configurable). It processes and stores weather conditions, performs daily rollups, and provides insights like: Average, Maximum, and Minimum Temperatures. Dominant Weather Condition for the day. User-configurable alerts based on threshold breaches (e.g., high temperatures).

Technologies Used:
Frontend: HTML, CSS, JavaScript
API: OpenWeatherMap API
Visualization Libraries: Chart.js (for visualizing trends and alerts)

Setup and Installation:
Prerequisites:
OpenWeatherMap API Key: Sign up for a free API key at OpenWeatherMap.
Web Server: You can use a simple HTTP server like http-server or run directly in your browser.

Instructions
Clone the Repository:
Configure API Key:
Open the script.js file in the root directory.
Replace YOUR_API_KEY with your actual OpenWeatherMap API key:
const API_KEY = 'YOUR_API_KEY';

Run the Project:
You can directly open the index.html file in your browser.
Alternatively, you can start a simple server:
