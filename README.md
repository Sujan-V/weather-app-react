 🌦️ React Weather App

This is a simple weather forecast application built using React. It fetches real-time weather data using the [OpenWeatherMap API](https://openweathermap.org/api) and displays it with dynamic background themes and weather icons based on the selected city.

🖼️ Features

- 🔍 Search for any city to get current weather data.
- 🌡️ Displays temperature, weather condition, and date.
- 🎨 Dynamic background changes based on weather condition.
- 🖼️ Custom weather icons.
- 📱 Responsive and modern UI design.

🚀 Live Demo : https://sujan-v.github.io/weather-app-react/

🛠️ Tech Stack

- React.js (Create React App)
- OpenWeatherMap API
- HTML + CSS (with Google Fonts & custom animations)


📦 Getting Started

1. Clone the repository : git clone https://github.com/your-username/your-repo-name.git
                          cd your-repo-name
2. Install dependencies : npm install
3. Replace the placeholder API key in App.js:  const API_KEY = "YOUR_API_KEY_HERE"; Get your API key from https://openweathermap.org/api
4. Run locally : npm start

🛠️ Build for Production
npm run build   //This will generate a build/ folder with optimized production-ready files.

🚢 Deployment Options
GitHub Pages
1. Install gh-pages : npm install --save-dev gh-pages
2. Update package.json
    "homepage": "https://your-username.github.io/your-repo-name",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}

3. Deploy : npm run deploy

For Reference Watch : https://youtu.be/7wzuievFjrk?si=DVwz_wtYIjdNuWyF

📂 File Structure

my-weather-app/
├── public/
│   ├── index.html
│   └── *.png (weather icons)
├── src/
│   ├── App.js
│   └── index.js
├── README.md
├── package.json
└── ...


📸 Screenshots
![image](https://github.com/user-attachments/assets/e5f7ea4e-0380-4d13-99ff-573ee6cfbbfc)
![image](https://github.com/user-attachments/assets/16418847-0369-4d32-8187-612693f519f9)

🙌 Acknowledgments

OpenWeatherMap
React
Google Fonts - Inter

