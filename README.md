# Power BI Weather Analysis
Weather Analysis Project in Power BI
Sure! Here's your finalized and combined **README.md** for the **Power BI Capstone Project – Weather Analysis**, including the dataset link and all sections cleanly formatted and professional:

---

# 🌦️ Power BI Capstone Project – Weather Analysis

This is my final capstone project for Power BI, aimed at analyzing and visualizing global weather trends through interactive dashboards and data-driven insights.

📁 **Solution Link**: [Google Drive – Project Files](https://drive.google.com/drive/folders/18r-Pn4C_DhWSydFqz_iyoVALTq6qrVyX?usp=drive_link)

---

## 📌 Overview

The **Weather Analysis Project** explores global meteorological patterns using structured weather data — including temperature, humidity, pressure, wind speed, and wind direction — across multiple cities and time periods. The project is designed to support:

* **Urban planning**
* **Climate research**
* **Disaster preparedness**
* **Energy management**

A complete end-to-end approach was taken, combining **Power BI dashboards**, **EDA in Excel**, and **SQL-based relational modeling**.

---

## 🎯 Objectives

* Analyze **seasonal patterns** and anomalies in weather metrics.
* Evaluate **city-wise** and **country-wise** variations in climate behavior.
* Build **interactive dashboards** in Power BI for visual storytelling.
* Use **EDA techniques** to discover correlations and trends.
* Enable data-backed decisions in **climate-sensitive sectors**.

---

## 🛠️ Tools & Technologies

* **Power BI** – For creating dynamic visual reports and dashboards
* **Excel** – For exploratory data analysis and prototyping
* **MySQL Workbench** – For database schema design and querying
* **GitHub** – For version control and documentation

---

## 🧰 Dataset & Schema

The dataset includes multiple tables integrating temporal and geographic dimensions, enabling multi-faceted weather analysis.

📥 **[Download Dataset (Google Drive)](https://drive.google.com/drive/folders/18r-Pn4C_DhWSydFqz_iyoVALTq6qrVyX?usp=drive_link)**

### 📂 Core Tables

* **`final_fact`** – Weather measurements
  ![image](https://github.com/user-attachments/assets/8e1fc06c-9a4d-4ece-bb88-5ab1caf71e56)

* **`city_lookup`** – City metadata
  ![image](https://github.com/user-attachments/assets/701dfaed-7011-49ab-845f-355669e52a06)

* **`country`** – Country reference table
  ![image](https://github.com/user-attachments/assets/05b451f1-146f-4fe8-a652-e988b97cd1ba)

* **`city_attributes`** – Latitude and longitude data
  ![image](https://github.com/user-attachments/assets/e3c12351-71c6-4434-811a-e379e455fc6f)

* **`date_lookup`, `time_lookup`** – Temporal dimensions
  ![image](https://github.com/user-attachments/assets/f256b52f-890b-4b66-8d72-76c00f80a77c)

### 🔑 Key Columns

| Table             | Column              | Description                 |
| ----------------- | ------------------- | --------------------------- |
| `final_fact`      | temperature         | Temperature in Celsius      |
| `final_fact`      | humidity            | Humidity percentage (%)     |
| `final_fact`      | pressure            | Atmospheric pressure in hPa |
| `final_fact`      | wind\_speed         | Wind speed in m/s           |
| `city_attributes` | latitude, longitude | Geographic coordinates      |

---

## 📊 Power BI Visualizations

A variety of data visualizations were designed in Power BI to uncover trends, patterns, and anomalies:

* 🌍 **Maps** – City locations using latitude/longitude
  ![image](https://github.com/user-attachments/assets/9ef3f3ba-71cb-4f79-bfc0-2d2812d4c641)

* 📊 **Bar Charts** – Top countries by number of cities, extreme temperatures
  ![image](https://github.com/user-attachments/assets/444c7b4e-0f5b-49ea-b275-8fb5104c0868)

* 📈 **Line Charts** – Temperature variations over time (global/city-specific)
  ![image](https://github.com/user-attachments/assets/ae05a67f-6745-46b4-a348-620d9af47b44)

* 🌡️ **Heatmaps**

  * Humidity levels
    ![image](https://github.com/user-attachments/assets/47b94d16-5230-4ec5-b152-aef4918f3598)
  * Wind speed by month
    ![image](https://github.com/user-attachments/assets/034408b9-7924-4478-83c7-0036d281f1e3)
  * Busiest weather hours
    ![image](https://github.com/user-attachments/assets/dbfb5e30-bd4a-4ed9-979e-bce8b75f2e3e)

* 🌀 **Radial/Wind Rose Charts** – Wind direction and diurnal wind speeds
  ![image](https://github.com/user-attachments/assets/a5d7db61-67b0-4f9a-bdb2-34271f4d7256)
  ![image](https://github.com/user-attachments/assets/2f72dae1-86c4-4c6f-9586-b23ea3a00751)

* ⚡ **Scatter Plots** – Wind speed vs air pressure
  ![image](https://github.com/user-attachments/assets/edc7f017-e15b-4a24-83be-095a2a024b05)

Each visualization helps drive understanding in areas like smart city planning, disaster response, and weather readiness.

---

## 📈 MECE Breakdown (Problem Segmentation)

The MECE (Mutually Exclusive, Collectively Exhaustive) framework was used to segment problem areas effectively across four domains:

* **Climate Pattern Analysis** – e.g., temperature shifts, humidity trends
* **Weather Conditions** – Types, frequency, and severity
* **Correlation Analysis** – Pressure-humidity, temperature-wind relationships
* **Location-Based Insights** – City/country extremes and patterns

📄 Refer to the MECE\_Breakdown.pdf
![image](https://github.com/user-attachments/assets/6dd26ff2-443e-4bad-9346-74bea7246dd0)

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was conducted in Excel and MySQL to prepare, clean, and analyze weather patterns before visualization.

![image](https://github.com/user-attachments/assets/c82ebdcc-7617-4e51-a2b4-55b23d7890e4)

### 🔍 Key Insights:

* 🌐 Do cities at similar latitudes share climate traits?
  ![image](https://github.com/user-attachments/assets/5de1eadb-51f4-477a-9a61-e47443011f78)

* 🌧️ Which cities are rainiest, and in what seasons?
  ![image](https://github.com/user-attachments/assets/1277ab5a-caef-4a16-9c61-d3aba9b95ad1)

* 💧 How does humidity relate to pressure?
  ![image](https://github.com/user-attachments/assets/c9ee6af6-1982-42be-a420-b33c362b9f85)

* 📆 Which months show highest temperature swings?
  ![image](https://github.com/user-attachments/assets/722631f6-26e1-4abb-aa93-e458f14d8b69)

* ⚡ How do extreme temperatures impact energy usage?
  ![image](https://github.com/user-attachments/assets/1515747c-af99-4db4-b5de-d31a51ca0878)

---

## ✅ Summary

This capstone project showcases how structured data modeling, EDA, and interactive visual storytelling can work together to solve real-world problems related to climate and weather analytics. It provides scalable, decision-ready insights for professionals working in urban infrastructure, disaster mitigation, and environmental research.

---

Let me know if you'd like this exported as a Markdown file or need a formatted PDF version!

