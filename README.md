ESP32 Solar Weather Monitor with OLED Display

This project is a Solar Weather Monitoring Station built using an ESP32-C3 and a 128×64 OLED display. The device connects to Wi-Fi and retrieves real-time space weather data from the NOAA Space Weather Prediction Center (SWPC) APIs. It displays important solar activity information that can affect radio communications, satellites, GPS systems, and aurora visibility.

The system continuously downloads and displays:

Kp Index – a measure of geomagnetic storm activity.
Solar Wind Speed – the velocity of charged particles flowing from the Sun.
Solar Wind Density – the concentration of solar particles in space.
Solar Wind Temperature – the temperature of the solar plasma.

The ESP32 processes the NOAA JSON data and presents the latest values on the OLED screen in an easy-to-read format. Data is refreshed automatically every minute, providing near real-time monitoring of current space weather conditions.

Features
Real-time NOAA space weather data
Wi-Fi connectivity
128×64 OLED display
Live Kp Index monitoring
Solar wind speed, density, and temperature readings
Automatic updates every 60 seconds
Serial Monitor debugging output
Hardware Used
ESP32-C3 Development Board
SSD1306 128×64 OLED Display (I2C)
Wi-Fi Internet Connection
Applications
Amateur radio monitoring
Aurora forecasting
Space weather education
Satellite and GPS activity observation
STEM and astronomy projects

This project demonstrates how an ESP32 can be used to access online scientific data sources and create a compact, real-time solar weather dashboard for hobbyists, students, and space enthusiasts.
