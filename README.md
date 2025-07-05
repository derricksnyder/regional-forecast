# NWS Regional 6-Day Forecast Dashboard

This project displays a regional 6-day weather forecast averaged from several key cities in the National Weather Service (NWS) Paducah, KY forecast area. It uses real-time XML forecast data from the NWS and renders it in a clean, responsive dashboard optimized for both desktop and mobile devices.

## 🌐 Live Demo

👉 [View the dashboard here](https://derricksnyder.github.io/regional-forecast/)  

---

## 📦 Features

- ✅ Live 6-day forecast for **7 regional cities**
- 📍 Averaged high and low temperatures
- 🌤️ Weather summary and icon for each day
- 🇺🇸 Highlights **U.S. federal holidays**
- 📱 Fully responsive and **mobile-friendly**
- 🌀 Loading and error handling states
- 🎨 Built with [Tailwind CSS](https://tailwindcss.com/)

---

## 📍 Forecast Locations

- Marion, IL  
- Paducah, KY  
- Owensboro, KY  
- Evansville, IN  
- Poplar Bluff, MO  
- Cape Girardeau, MO  
- Mount Vernon, IL  

---

## 🛠️ How It Works

- Fetches DWML (XML) forecast data from:  
  `https://forecast.weather.gov/MapClick.php?...&FcstType=dwml`
- Parses temperature, weather summary, and icon data
- Averages forecast data across all cities
- Displays a summarized forecast card for each day

---

## 💻 Technologies Used

- **HTML5**
- **Tailwind CSS** (via CDN)
- **Vanilla JavaScript**
- **NWS DWML API**
- **GitHub Pages** for deployment

---

## 🚀 Deploy Your Own

1. Fork or clone this repository
2. Replace or edit `index.html` as needed
3. Push to `main` branch
4. Enable GitHub Pages from repo settings
5. Done! Your site is live

---

## 📄 License

This project is open-source and uses publicly available data from the U.S. National Weather Service (NWS).

---

## 👨‍💻 Author

Built by Derrick Snyder
Feel free to suggest improvements or open issues!

