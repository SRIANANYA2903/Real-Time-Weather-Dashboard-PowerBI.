**🌦️ Real-Time Weather & Environmental Analytics Dashboard
Project Overview**

This project features a dynamic, real-time Weather Dashboard developed in Power BI. It integrates live data from the WeatherAPI to provide users with up-to-date meteorological and environmental insights for any city, specifically optimized for the Banglore,Mumbai,Namakkal,Salem,Hydrebad,Chennai
The dashboard is designed with a modern "Glassmorphism" aesthetic, focusing on both data accuracy and user experience.

**Live Preview**
<img width="1661" height="935" alt="image" src="https://github.com/user-attachments/assets/3580cd48-7ff5-43f6-be82-ee3406c09169" />

**Key Features**
Real-time Data Stream: Connected to the v1/forecast.json endpoint to fetch current weather conditions.
3-Day Forecasting: A specialized trend analysis showing temperature fluctuations over a 72-hour window.
Environmental Tracking: Comprehensive Air Quality Index (AQI) monitoring, including PM2.5, SO2, and NO2 levels.
Advanced UI: Dark-themed interface utilizing semi-transparent "frosted glass" cards and orange-to-black gradients for a premium feel.
Automated Pipeline: Configured with Scheduled Refreshes in Power BI Service to ensure hands-free, daily updates.

**Technical Implementation (ETL & Modeling)**
API Ingestion: Ingested raw JSON data via Web Connector.
Data Cleaning: Used Power Query (M Language) to expand nested records, remove duplicates from the forecast list, and normalize data types.
Time Intelligence: Converted Unix Epoch timestamps into standard Date/Time formats for accurate time-series plotting.
Credential Management: Configured Anonymous authentication with Public privacy settings for seamless cloud refreshing.

**How to Use This Project**
Download: Download the Weather_Analytics_Dashboard.pbix file from this repository.
Open: Launch the file in Power BI Desktop.
API Key: To refresh the data, you will need a free API key from WeatherAPI.com.
Update Source: Go to Transform Data > Data Source Settings and update the URL with your unique API key.

**Tools & Technologies**
**BI Tool**: Microsoft Power BI
**Language**: Power Query (M)
**Data Source**: WeatherAPI (JSON)
**Design Concept**: Glassmorphism UI/UX
