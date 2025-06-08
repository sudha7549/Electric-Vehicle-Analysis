# Electric-Vehicle-Analysis

This project presents an interactive and data-rich **Electric Vehicle Analysis Dashboard** built in **Power BI**. It provides insights into the adoption of electric vehicles (EVs) across the United States, with breakdowns by model year, manufacturer, CAFV eligibility, and more.

---

## 📊 Dashboard Overview

The dashboard is designed to help users:
- Analyze the **total number of electric vehicles** and their **average electric range**
- Understand the **distribution of BEVs vs. PHEVs**
- Track **vehicle popularity trends by year, make, and model**
- Visualize **state-wise EV distribution** across the U.S.
- Evaluate **CAFV eligibility** for tax or environmental benefits
- Use **dynamic filters** (City, Electric Utility, EV Type) to drill into specific segments

---

## 🧮 Key DAX Measures Used

- `Total Vehicles = COUNT(Vehicle ID)`
- `BEV Vehicles = SUM(BEV Vehicles)`
- `PHEV Vehicles = SUM(PHEV Vehicles)`
- `% of Total = DIVIDE(Vehicle Type Count, Total Vehicles)`
- `Avg Electric Range = AVERAGE(Electric Range)`
- Visual-level measures for Model Year, Make, State, and CAFV breakdowns

---

## 🛠️ Tools & Technologies

- Power BI (DAX, Data Modeling, Slicers)
- Data Transformation via Power Query
- Visuals: Line Chart, Map, TreeMap, Donut Chart, Bar Chart, Card

---

## 📂 Files Provided

- `Electric_Vehicle_Analysis.pbix` – Power BI report file  
- `EV_Practice_Dataset.xlsx` – Excel sheet for practice  
- `Screenshots/` – Folder with preview PNGs of the dashboard  

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Optionally explore and modify the Excel sheet to load custom data.
4. Use filters to analyze data across different states, cities, and vehicle types.

---

## 📸 Dashboard Preview

![EV Dashboard ➡️ https://www.linkedin.com/posts/sudhanshu-kumar-714b72296_electric-vehicle-analysis-dashboard-activity-7337337375334813698-W72F?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEe4LIABj2nCyO9IAZ7JuvcSqUXezwbGT-E]

---

## 📬 Let's Connect!

If you're interested in data storytelling, sustainability, or BI tools, feel free to connect with me on [LinkedIn](https://www.linkedin.com).  
Happy analyzing! 📈

---

**#PowerBI #ElectricVehicles #Dashboard #DataAnalytics #DAX #Sustainability #EVAnalysis**
