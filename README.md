# Weather_Forecast
 A real-time data processing system to monitor weather conditions and provide summarized insights using rollups and aggregates. The system will utilize data from the OpenWeatherMap API (https://openweathermap.org/)

This project fetches real-time weather data for major Indian metros like Delhi, Mumbai, Chennai, Bangalore, Kolkata, and Hyderabad, every 5 minutes (configurable). It processes and stores weather conditions, performs daily rollups, and provides insights like:
Average, Maximum, and Minimum Temperatures.
Dominant Weather Condition for the day.
User-configurable alerts based on threshold breaches (e.g., high temperatures).

Technologies Used 
Frontend: HTML, CSS, JavaScript 
API: OpenWeatherMap API 
Visualization Libraries: Chart.js (for visualizing trends and alerts)

API Information 
OpenWeatherMap API: The system retrieves weather data using the /weather endpoint of OpenWeatherMap for each metro city. The data fetched includes:
main: Main weather condition (e.g., Rain, Clear).
temp: Temperature in Kelvin (converted to Celsius).
feels_like: Perceived temperature in Kelvin.
dt: Timestamp of the update.
