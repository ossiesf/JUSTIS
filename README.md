# JUSTIS-Inspired Criminal Justice Data Integration & Visualization

This project simulates a lightweight version of San Francisco's JUSTIS data exchange hub. It integrates structured crime data with weather and policy context, processes that data with Python and PL/SQL, and visualizes insights using Power BI.

## 🚀 Project Goals

* Demonstrate a backend data ingestion pipeline using Python and SQLite
* Build a simple Oracle APEX app to simulate criminal justice record interaction
* Visualize crime trends in Power BI, enriched with weather and policy overlays
* Highlight how policy changes—like SF's 2024 **Pretextual Traffic Stop Ban**—may affect crime patterns

## 🛠️ Tech Stack

* **Python** – Data transformation and API integration (OpenWeather + CSV wrangling)
* **Oracle APEX / PL/SQL** – Form-based data interaction and stored procedures
* **Power BI** – Visualization of key metrics and patterns
* **Git & GitHub** – Version control and collaboration

## 📊 Data Sources

* [SF Police Incident Reports (OpenData)](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present)
* [Visual Crossing Weather API](https://www.visualcrossing.com/weather-api) for historic weather
* Policy timeline: SF Board of Supervisors / public news sources

## 📈 Visualized Metrics

* Crime count over time, filtered by category and district
* Distribution of arrests vs non-arrests on pretextual stops (simulated via traffic codes)
* Correlation between daily temperature and incident types
* Policy event overlays (e.g., 2024 pretext stop ban)

## 📂 Folder Structure

├── data/ # Raw + cleaned CSVs
├── notebooks/ # Python scripts for ingestion & transformation
├── apex/ # APEX exports & screenshots
├── dashboard/ # Power BI files and visuals
└── README.md # You are here