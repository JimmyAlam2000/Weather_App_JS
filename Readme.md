🌤️ Weather App

A simple and clean weather application built using HTML, CSS, and vanilla JavaScript.
It fetches real-time weather data from the OpenWeatherMap API and displays temperature, humidity, weather description, and an emoji-based weather icon.


---

🚀 Features

🔍 Search weather by city name

🌡️ Shows temperature (°C)

💧 Displays humidity

☁️ Shows weather description

😀 Weather emoji icons based on condition

⚠️ Error handling for invalid city or failed API request

🧩 Fully written in vanilla JavaScript — no frameworks




---

🛠️ Technologies Used

HTML5

CSS3

JavaScript (ES6+)

OpenWeatherMap API



---

🔑 Setup & Installation

1. Clone the repository

git clone https://github.com/yourusername/weather-app.git


2. Navigate into the project

cd weather-app


3. Open index.html in your browser
No build tools needed — runs directly in the browser.




---

🔐 API Setup

This app uses the OpenWeatherMap API.

1. Sign up here:
https://openweathermap.org/api


2. Get your API key.


3. Replace this line in your JavaScript:



const apiKey = "Generate and use your own api keys";

4. Replace the API URL:



const apiUrl = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}`;


---

📂 Project Structure

weather-app/
│── index.html
│── style.css
│── script.js
└── README.md


---

🧠 JavaScript Highlights

✔ Async/Await for clean API requests
✔ Destructuring for easy data extraction
✔ Dynamic DOM creation
✔ Weather ID → Emoji mapping using switch-case
✔ Proper error handling

Example snippet:

const { name, main: { temp, humidity }, weather: [{ description, id }] } = data;


---

🐛 Error Handling

If user enters an invalid city or API fails, the app shows:

"Could not fetch weather data"

or

"Please enter a city"


---

📌 Future Improvements (Optional)

Add 5-day forecast

Add Fahrenheit toggle

Add background images based on weather

Deploy using GitHub Pages



---

📜 License

This project is open-source and free to use.


---