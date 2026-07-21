# Smart Farming: Crop Yield Analytics Dashboard

An interactive Power BI dashboard analyzing the Smart Farming Crop Yield 2024 dataset — exploring how environmental conditions and farming practices affect crop yield across regions and crop types.

## 📊 Overview

This dashboard brings together agronomic, environmental, and farming-practice data to help identify which conditions and practices are associated with higher (or lower) crop yield.

## 📁 Dataset: `Smart_Farming_Crop_Yield_2024`

**Environmental factors:**
- `soil_moisture_%`, `soil_pH`
- `NDVI_index` (vegetation health index)
- `rainfall_mm`, `temperature_C`, `humidity_%`, `sunlight_hours`

**Farming practices:**
- `crop_type`, `region`
- `fertilizer_type`, `irrigation_type`
- `pesticide_usage_ml`
- `crop_disease_status`

**Time dimensions:**
- `sowing_date`, `timestamp` (analyzed by month)

**Target metric:**
- `yield_kg_per_hectare`

## 📈 Dashboard Features

- Regional and crop-type breakdown of average yield
- Yield trends by month (sowing date / timestamp)
- Correlation view between yield and environmental factors (soil moisture, soil pH, NDVI index, rainfall, temperature, humidity, sunlight hours)
- Comparison across fertilizer types, irrigation types, and pesticide usage levels
- Crop disease status tracking against yield outcomes

## 🔍 What This Dashboard Helps Answer

- Which regions and crop types achieve the highest yield?
- How do soil and weather conditions (moisture, pH, rainfall, temperature) correlate with yield?
- Does fertilizer type or irrigation method make a measurable difference?
- How does crop disease status impact final yield?

## 🛠️ Tools Used

- **Power BI** — data modeling, DAX measures, and dashboard visuals
- **Power Query** — data loading and transformation

## 📂 Files

- `agriculture_dashboard.pbix` — Power BI report file (open with [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop), free)

## 📸 Preview

*(Add a screenshot here — export a view of the dashboard as PNG and reference it: `![dashboard preview](screenshot.png)`)*

---
*Project by Gaurvi Jain*
