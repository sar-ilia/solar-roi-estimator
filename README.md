# ☀️ Solar ROI Estimator

**Solar ROI Estimator** is an interactive web application for calculating the return on investment (ROI) of residential photovoltaic (PV) systems in the Czech Republic.

Users can enter their annual energy consumption, location, and system parameters — the app then estimates how quickly the investment will pay off, using real solar irradiance data from the PVGIS database.

---

## 🔧 Tech Stack

- **Next.js** – React-based web framework  
- **TypeScript** – static type safety  
- **TailwindCSS** – utility-first CSS framework  
- **Recharts** – for interactive ROI charts  
- **Leaflet** – for interactive map input  
- **PVGIS API** – public solar irradiance data by EU

---

## ✨ Features

- ROI calculation based on:
  - ⚡️ Annual energy consumption
  - 🌍 Geographic location
  - 💰 Electricity tariff
  - 🔋 Battery system (optional)
  - 🚗 Electric vehicle integration
- Real-time solar data fetch from **PVGIS** based on user-selected coordinates
- Interactive ROI charts showing savings over time
- EV support: choose common models or enter custom consumption
- Select location directly from an interactive map (**Leaflet**)

---

## 🖥️ Demo

Coming soon...

---

## 📦 Local Setup

```bash
git clone https://github.com/sar-ilia/solar-roi-estimator.git
cd solar-roi-estimator
npm install
npm run dev
