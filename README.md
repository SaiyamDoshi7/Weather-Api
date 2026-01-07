🌦 Weather Information Web App
📌 Project Overview

This is a Weather Information Web Application built using HTML, CSS, and JavaScript.
The app allows users to search for any city and view real-time weather information using the OpenWeatherMap API.

The UI is divided into two sections:

Left Card: Displays day, date, weather icon, temperature, and condition

Right Panel: Displays search input and detailed weather data

✨ Features

🔍 Search weather by city name

🌡 Displays current temperature in Celsius

💧 Shows humidity percentage

🌬 Shows wind speed

🌤 Dynamic weather icons (SVG based)

📅 Auto-updated day and date

⚠ Error message for invalid city name

🎨 Clean and modern UI (exam-safe & original)

🛠 Technologies Used

HTML5 – Structure of the web app

CSS3 – Styling and layout (Flexbox)

JavaScript (ES6) – Logic, API handling, DOM manipulation

OpenWeatherMap API – Real-time weather data

🔗 API Used

OpenWeatherMap – Current Weather API

https://api.openweathermap.org/data/2.5/weather


Parameters used:

q → City name

units=metric → Temperature in Celsius

appid → API key

📂 Project Structure
Weather-App/
│
├── index.html
├── style.css
└── README.md

⚙ How It Works

User enters a city name in the search box

JavaScript fetch() sends request to the Weather API

API returns weather data in JSON format

Data is extracted and displayed dynamically on the UI

Both left card and right panel update simultaneously

🚀 How to Run the Project

Download or clone the project

Open index.html in any modern web browser

Enter a city name (e.g., Surat, Delhi, Mumbai)

Click Search or press Enter

🧪 Example Cities to Test

Surat

Mumbai

Delhi

London

New York
