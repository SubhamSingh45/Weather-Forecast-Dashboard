# 🌦️ Weather Forecast Dashboard

## 📊 Overview
This Power BI dashboard is a complete **7-Day Weather Forecast + Air Quality Index (AQI)** visual solution built using **live data from a Weather API**. The dashboard is interactive, multi-city capable, and designed for real-time analytics with built-in suggestions based on the AQI level for each city.

---

## 🔍 Key Features
- 🌐 **Live Weather & AQI API Integration**  
- 🧹 **Data Cleaning & Transformation** with Power Query  
- 🧠 **Custom DAX Measures** for dynamic insights  
- 🗓️ **7-Day Forecast**: Temperature, humidity, and pressure
- 🌫️ **Air Quality Index (AQI)** with automatic health **recommendations**  
- 🏙️ **Multi-City Support** – view forecast & AQI for selected cities  
- 📱 **Mobile-friendly, visually clean dashboard UI**

---

## 🧩 Tools & Technologies Used
- **Power BI Desktop**
- **Live Weather API** (e.g., weatherapi.com)
- **DAX (Data Analysis Expressions)**
- **Power Query**

---

## 💡 How It Works
1. **Live Data Import:** Used *Get Data > Web* to connect with a weather API for real-time updates.
2. **Data Cleaning:** unnecessary columns removed, removed duplicates using Power Query.
3. **Modeling:** Relationships set up, with calculated columns and DAX measures.
4. **Dashboard Design:** Forecast and AQI visuals with slicers for city selection.
5. **Suggestions Engine:** Based on AQI value, DAX conditions generate city-wise tips like:
   - *"Air quality is poor. Avoid outdoor activities."*
   - *"Moderate air quality. Sensitive individuals should reduce prolonged exposure."*

---

## 🏙️ Sample Cities Included
- Mumbai  
- Bengaluru  
- Hyderabad  
- Chennai  
- Vizag
- Raipur,
  and many more...

---

## 📌 Sample KPIs Displayed
| Metric                   | Example Value     |
|--------------------------|-------------------|
| Current Temperature      | 33.5 °C           |
| Forecasted Max Temp      | 36.2 °C (in 3 days)|
| Humidity                 | 71%               |
| AQI (PM2.5)              | 165 (Unhealthy)   |
| AQI Recommendation       | "Wear a mask if going outdoors." |

---
---

## 🧠 Learning Outcomes
- Connecting APIs with Power BI using “Web” data source
- DAX-based conditional formatting and dynamic messages
- multi-city reporting setup
- Real-world domain exposure: Weather + Environmental Analytics

---

## 📌 Note
This dashboard is designed for **educational and demonstration purposes only** using free API sources. Accuracy may vary due to public API limits.

---



