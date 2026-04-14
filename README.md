 <h1>🌦️ Weather App</h1>

<p>A simple and responsive weather application that allows users to search for any city and view real-time weather details including temperature, conditions, and humidity.</p>
<br/>
<h2>📌 Features</h2>
<ul>
  <li>🔍 Search weather by city name</li>
<li>🌡️ Displays real-time temperature (°C)</li>
<li>☁️ Shows weather conditions (e.g., cloudy, clear, rain)</li>
<li>💧 Displays humidity levels</li>
<li>🌙 Toggle between Dark Mode and Light Mode</li>
<li>🔄 Refresh button to reload weather data</li>
<li>📱 Fully responsive design for multiple screen sizes</li>
</ul>
<br/>
<h2>🛠️ Tech Stack</h2>
<ul>
  <li>HTML5 – Structure of the application</li>
<li>CSS3 / Tailwind CSS – Styling and responsiveness</li>
<li>JavaScript (ES6+) – Application logic and DOM manipulation</li>
<li>Vite – Build tool for fast development</li>
<li>OpenWeatherMap API – Fetching real-time weather data</li>
</ul>
<br/>
<h2>🚀 How It Works</h2>
<ol>
  <li>User enters a city name</li>
<li>The app stores the input using localStorage</li>
<li>A request is sent to the OpenWeatherMap API</li>
<li>Weather data is fetched and displayed dynamically</li>
</ol>
<br/>
<h2>📂 Project Structure</h2>
<p>├── index.html             # Landing page</p>
<p>├── weather.html           # Weather display page</p>
<p>├── src/</p>
<p>│   ├── main.js            # Main JavaScript logic</p>
<p>│   └── style.css          # Styles</p>
<p>├── dist/                  # Compiled CSS</p>
<br/>
<h2>⚙️ Setup Instructions</h2>
<ol>
  <li>Clone the repository
<code>git clone url </code></li>
<li>Navigate to the project folder
<code>cd weather-app</code></li>
<li>Install dependencies
<code>npm install</code></li>
<li>Create a .env file and add your API key
<code>VITE_WEATHER_API_KEY=your_api_key_here</code></li>
  <li>Run the development server
<code>npm run dev</code></li>
</ol>
<br/>

## 🔑 API Endpoint

This project uses OpenWeatherMap API:

https://api.openweathermap.org/data/2.5/weather

### Example Request:
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric

<br/>

## 🙌 Acknowledgements
- Weather data provided by OpenWeatherMap API
