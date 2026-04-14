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

1. Clone the repository  
```bash
git clone <your-repo-link>
```
 2. Navigate to the project folder  
```bash
cd weather-app
```

3. Install dependencies  
```bash
npm install
```

4. Run the development server  
```bash
npm run dev
```
<br/>

## 🔑 API Endpoint

This project uses OpenWeatherMap API:

https://api.openweathermap.org/data/2.5/weather

### Example Request:
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric

<br/>

## 🙌 Acknowledgements
- Weather data provided by OpenWeatherMap API
