# Household Electric Power Consumption Analysis

This project is a comprehensive web application designed to analyze and visualize household electric power consumption data. It allows users to select a specific date and view detailed statistics, including hourly power consumption, voltage trends, and sub-metering data. The application also provides insights into energy usage patterns over the past 7 days, helping users optimize their energy consumption.

---

## Features

- **Date Selection:** Users can select a specific date to analyze power consumption for that day.
- **Hourly Analysis:** View average, highest, and lowest power consumption with corresponding timestamps.
- **Sub-metering Insights:** Explore energy usage from specific appliances.
- **7-Day Trends:** Analyze power consumption trends over the past week.
- **Interactive Visualizations:** Generate interactive line charts and bar graphs for better understanding of energy usage patterns.

---

## Technologies Used

- **Backend:** Flask (Python) for handling data processing and server-side logic.
- **Frontend:** HTML, CSS, and JavaScript for the user interface.
- **Data Visualization:** Matplotlib for generating charts.

---

## How It Works

1. **Data Loading:** The application loads household power consumption data from a text file (`household_power_consumption.txt`).
2. **Data Processing:** The data is cleaned, and date-time columns are combined for easier analysis.
3. **Visualization:** Matplotlib is used to generate charts, which are then embedded in the web application using base64 encoding.
4. **User Interaction:** Users select a date, and the application dynamically generates visualizations and statistics for the selected date.

---
## Dataset

The dataset used in this project is the **Household Electric Power Consumption Dataset**, which can be found on [Kaggle](https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set/data). It contains measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. The dataset includes various electrical quantities and sub-metering values.

---
## Screenshots

### 1. Date Selection Screen
![Image](https://github.com/user-attachments/assets/9d16fb6a-8cf5-4db2-adc2-5f3216927bc0)
*Users can select a date using the date picker to analyze power consumption for that day.*

---

### 2. Statistics and General Overview
![Image](https://github.com/user-attachments/assets/e3ffaea9-773e-4d4d-ad38-3073e3a91087)
*The application displays detailed statistics, including average, highest, and lowest power consumption, along with interactive charts.*

---

### 3. Hourly Power Consumption Chart
![Image](https://github.com/user-attachments/assets/d009f779-7481-4a67-a3e8-0140b6953a44)  
*A line chart showing hourly power consumption for the selected date.*

---

### 4. Voltage vs. Power Consumption Chart
![Image](https://github.com/user-attachments/assets/904a75b3-efa5-4376-af9c-d0f403ed3ec1)
*A scatter plot showing the relationship between voltage and power consumption.*

---

### 5. Sub-metering Power Consumption Chart
![Image](https://github.com/user-attachments/assets/09f81c0e-3e9f-4648-9a41-85d870fbe7ac)
*A line chart displaying energy usage from specific appliances.*

---

### 6. Last 7 Days Analysis
![Image](https://github.com/user-attachments/assets/cfc0c6a8-7ebf-4147-ab43-d7738d2ac305)
*A bar chart showing power consumption trends over the past 7 days.*
