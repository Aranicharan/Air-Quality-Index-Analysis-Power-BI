# 🌫️ AQI Analysis — Power BI Dashboard

A Power BI report that visualizes **Air Quality Index (AQI)** data across Indian cities, tracking key air pollutants over time to support environmental insights and analysis.

---

## 📊 Dashboard Overview

The report contains a single page — **City Day Air Pollution** — with interactive visuals that allow users to explore AQI trends, compare cities, and monitor individual pollutant levels.

### Visuals Included

| Visual | Description |
|---|---|
| 🗺️ **Map** | Geographic distribution of AQI by city across India |
| 📊 **Clustered Bar Chart** | Top 5 most polluted cities by average AQI |
| 📈 **Line Chart** | AQI trend over the years |
| 📉 **Bar Chart** | Total AQI comparison across cities |
| 🃏 **KPI Cards** | Summarized totals for CO, NO, SO₂, and PM2.5 |
| 🔽 **Slicers** | Filter by **City** and **Year** |

---

## 🧪 Key Metrics & Pollutants Tracked

- **AQI** — Air Quality Index (primary measure)
- **CO** — Carbon Monoxide
- **NO** — Nitric Oxide
- **NO₂** — Nitrogen Dioxide
- **NOx** — Nitrogen Oxides
- **O₃** — Ozone
- **PM2.5** — Fine Particulate Matter
- **SO₂** — Sulfur Dioxide
- **Toluene** — Volatile organic compound
- **Xylene** — Volatile organic compound

---

## 🗂️ Data Source

The report uses a dataset named **`city_day air pollution`**, which contains daily air quality readings per city, including pollutant concentrations and computed AQI values.

---

## 🚀 Getting Started

### Prerequisites

- [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)

### Steps

1. Clone or download this repository
2. Open `AQI_Analysis.pbix` in Power BI Desktop
3. Use the **City** and **Year** slicers to filter the dashboard
4. Hover over map bubbles to see pollutant breakdowns in tooltips

---

## 📁 Repository Structure

```
📦 AQI-Analysis
 ┣ 📊 AQI_Analysis.pbix   # Power BI report file
 ┗ 📄 README.md           # Project documentation
```

---

## 📌 Key Insights

- Identifies the **top 5 most polluted cities** by average AQI
- Shows **year-over-year AQI trends** to track improvement or deterioration
- Maps **geographic pollution hotspots** across cities
- Provides a **quick snapshot** of major pollutant totals via KPI cards

---

## 🛠️ Tools Used

- **Power BI Desktop** — Report building and data modeling
- **DAX** — Measures and aggregations (Sum, Average)

---

## 📄 License

This project is for educational and analytical purposes. Please ensure compliance with the terms of your data source before redistribution.
