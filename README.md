Professional Weather Dashboard
This project is a clean, corporate-style Weather Dashboard, built for Day 4 of my #30DayCodingChallenge. It focuses on presenting weather data in a clear, professional, and user-friendly interface suitable for a business or data-centric application.

🚀 Project Overview
This web application provides a comprehensive and professional weather summary for cities worldwide. It moves beyond a simple display to offer a more robust dashboard experience with a clean, two-column layout that separates current conditions from future forecasts and additional details.

Key Features:
Professional UI: A clean, two-column layout with a professional color scheme and clear typography.

Current Weather Display: Shows the current temperature, weather condition, city name, and date in a prominent, easy-to-read format.

Detailed Information: Includes secondary data points like "Feels Like" temperature, humidity, and wind speed.

5-Day Forecast: Provides a multi-day forecast with high/low temperatures and weather conditions for the upcoming days.

Unit Conversion: A toggle allows users to seamlessly switch between Celsius (°C) and Fahrenheit (°F).

Dynamic API Integration: Fetches live data from the OpenWeatherMap API and handles loading and error states gracefully.

💻 Technologies Used
HTML5: For the semantic structure of the dashboard.

Tailwind CSS: For all utility-first styling, creating a responsive and professional layout.

Vanilla JavaScript: For all application logic, including:

Fetching data from the OpenWeatherMap API using async/await.

Handling user input and events.

Dynamically updating the DOM to display weather data.

Managing application state (e.g., temperature units).

🛠️ How to Run Locally
To get a local copy up and running, follow these simple steps:

Clone the repository:

git clone https://github.com/your-username/your-weather-repo-name.git

Navigate to the project directory:

cd your-weather-repo-name

Add your API Key:
Open the index.html file and find the <script> section. Inside, locate the following line:

const apiKey = 'YOUR_API_KEY_HERE';

Replace 'YOUR_API_KEY_HERE' with your actual API key from OpenWeatherMap.

Open index.html in your browser:
Simply double-click the index.html file to open it in your default web browser.

Acknowledgment
This project represents Day 4 of my 30-day coding challenge. It was an excellent exercise in fetching data from a third-party API, handling asynchronous operations, and designing a clean, professional user interface.
