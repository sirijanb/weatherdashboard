# 🌦️ Power BI Weather Dashboard

This repository contains a Power BI dashboard that visualizes real-time and 7-day forecasted weather data using the [WeatherAPI](https://www.weatherapi.com/). The dashboard displays key environmental parameters across selected cities and dates, providing clear insights for decision-making and analysis.

## 📊 Live Report

🔗 [View the Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTViNzFkNzItNGUzYi00MGEwLWFlMGYtMWIyNTFmNjM3YzYyIiwidCI6ImJmMTZiMmJjLWE1NmMtNDU3Yi05M2UzLWRhOGMyNTEyNWQ3YSJ9)

## 📌 Features

- **Current and Forecast Weather**: Displays temperature, humidity, wind speed, pressure, visibility, precipitation and UV index for the selected city.
- **Interactive Visuals**: Allows users to filter by city to explore weather trends.
- **Dynamic AQI & Climate Indicators**: Includes calculated metrics like minimum/maximum temperature and Air Quality Index (AQI).
- **Data Refresh Logic**: Set up with a direct connection to WeatherAPI for periodic data refresh (via Power BI Service).
- **User-Friendly Layout**: Clean design tailored for easy comprehension of key weather stats.

## 🔧 Technologies Used

- [Power BI](https://powerbi.microsoft.com/)
- [WeatherAPI](https://www.weatherapi.com/)
- DAX (Data Analysis Expressions)
- Measures
- Power Query

## 📚 Learnings
Developing this Power BI Weather Dashboard provided hands-on experience and deepened my understanding in several areas:

- **Power BI Data Modeling**: Learned to design efficient data models that support dynamic filtering, aggregation, and visualizations across time and geography.

- **DAX Calculations**: Built custom measures using DAX to compute metrics such as minimum/maximum temperature, average humidity, and AQI values based on pollutant concentrations.

- **API Integration in Power BI**: Connected Power BI to an external weather API using Power Query. Understood how to format, transform, and handle JSON responses for analytical purposes.

- **Time-based Filtering and Refresh**: Implemented dynamic filtering based on current date and city, and configured scheduled refresh logic suitable for dashboards requiring live or frequently updated data.

- **Visualization Best Practices**: Focused on clean, user-friendly design with slicers, cards, line charts, and maps that make data easily digestible.

- **Error Handling & Data Transformation**: Managed null values, API rate limits, and implemented logic to ensure consistent and reliable data loading and processing.

This project greatly enhanced my data storytelling, problem-solving, and end-to-end dashboard development skills in Power BI.
