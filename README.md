# 🚀 Crypto Pulse

**Crypto Pulse** is a modern React-based cryptocurrency dashboard that fetches live data from the CoinGecko API. Users can browse coins, view 7-day price charts, search coins, and mark favorites. Designed with responsive UI and smooth UX in mind.

---

## 🔧 Features

- 📈 Real-time market data from [CoinGecko API](https://www.coingecko.com/)
- 🔍 Live search functionality
- ⭐ Add/remove favorites (stored in `localStorage`)
- 📊 7-day price chart with [Chart.js](https://www.chartjs.org/)
- 🔄 Infinite scroll / pagination
- 🎨 Responsive, modern UI (mobile-first)

---

## 🛠️ Built With

- [React](https://reactjs.org/)
- [React Router DOM](https://reactrouter.com/)
- [Chart.js](https://www.chartjs.org/) + [react-chartjs-2](https://github.com/reactchartjs/react-chartjs-2)
- [Axios](https://axios-http.com/)
- [CoinGecko API](https://www.coingecko.com/en/api)

---

## 📸 Preview

![App Screenshot](https://via.placeholder.com/800x400?text=Add+Your+Screenshot+Here)

---

## 📂 Folder Structure

CryptoPulse/
├── public/
├── src/
│ ├── components/
│ │ ├── CoinCard.js
│ │ ├── Navbar.js
│ │ └── PriceChart.js
│ ├── pages/
│ │ ├── Home.js
│ │ └── CoinDetails.js
│ ├── utils/
│ │ └── api.js
│ ├── App.js
│ ├── index.js
│ └── App.css
└── README.md
