# Mausam - Personalized National Weather Intelligence Engine (PS-26076)

A next-generation, context-aware meteorological web platform engineered to transform standard weather forecasts into dynamic, actionable insights tailored for specific user personas—including commuters, agriculturalists, health-conscious individuals, and outdoor fitness enthusiasts.

---

## 🚀 Key Features & Modules

### 1. Apple Weather Desktop Interface (`index.html`)
* **Glassmorphism UI/UX:** Built with translucent frosted glass cards, smooth typography, and a sleek dark theme inspired by premium weather applications.
* **Live Telemetry & Geocoding:** Integrated directly with **Open-Meteo API** to fetch real-time atmospheric data (temperature, humidity, precipitation, wind speed, and 7-day forecasts) with zero API-key friction.
* **Side-by-Side City Navigation:** Switch instantly between major national hubs (New Delhi, Mumbai, Bengaluru, Chennai) or search any global location.

### 2. Dedicated Agricultural Hub (`agriculture.html`)
* **Custom Crop & Soil Profiling:** Allows farmers to input specific crop types (e.g., Wheat, Rice) and growth stages (Vegetative, Flowering, Harvesting).
* **AI Agronomist Q&A Assistant:** Farmers can ask natural language questions regarding fertilizer timing, humidity-driven pest risks, or harvesting windows to receive instant contextual advice.

### 3. Mode-Adaptive Transit Hub (`commuter.html`)
* **Multi-Modal Personalization:** 
  * 🚶 **Walking Mode:** Focuses on pedestrian walkway comfort, air quality (AQI), and UV safety.
  * 🚲 **Cycling Mode ("Yellow Cycle Theme"):** High-energy high-contrast theme tracking wind gusts, side-wind impact, and road slickness.
  * 🚗 **Car & Transit Mode:** Live highway visibility range, fog warnings, and precipitation radar.
* **Route Customization:** Takes explicit **From** and **To** location inputs to compute route-specific weather synchronizations.

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, Vanilla JavaScript, Tailwind CSS (via CDN)
* **Design System:** Apple SF Pro typography, custom glassmorphism styling, and dynamic CSS themes.
* **Weather Data Feeds:** Open-Meteo REST API (Real-time meteorological metrics, WMO weather codes, and geocoding).

---

## 📂 Project Repository Structure
```text
mausam-app/
├── index.html          # Main Apple Weather Desktop Dashboard & Live API integration
├── agriculture.html    # Dedicated Agricultural Hub & AI Crop Assistant
├── commuter.html       # Mode-Adaptive Transit Hub (Car, Walk, Yellow Cycle Theme)
└── README.md           # Comprehensive project documentation
