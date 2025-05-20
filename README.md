# 🏘️ Tehran Housing Dashboard – Power BI

This interactive Power BI dashboard analyzes housing data from Tehran, including over 3,400 listings with detailed attributes such as price (in Rial and USD), area (m²), number of rooms, and building facilities like elevator, parking, and storage.

## 📌 Features

### 🔹 Page 1 – Overview
- Key KPI cards: 
  - Total number of listings
  - Average price (Rial)
  - Average price (USD)
  - Elevator - Praking Percentage per House
- Bar chart: Top 22 most expensive districts by average price
- Scatter plot: Relationship between area and price

### 🔹 Page 2 – Features Analysis
- Stacked column chart: Comparison of facility availability (Elevator, Parking, Storage)
- Custom DAX KPI: Percentage of homes with both elevator and parking

## 📊 Technologies Used
- Power BI Desktop
- Power Query (for data cleaning and unpivoting)
- DAX (for calculated measures and KPI logic)

## 💡 Key Insights
- More than **70%** of listings have an elevator
- Listings in areas like **Zafaraniyeh** and **Velenjak** have prices significantly higher than average
- The relationship between price and area is generally positive, but with visible outliers
- **60.4%** of homes have both **parking** and **elevator**

## 📁 Repository Contents
- `Tehran_Housing_Analysis.pbix` → Power BI dashboard file
- `dashboard_screenshot_1.png`, `dashboard_screenshot_2.png` → Screenshots of both dashboard pages
- `README.md` → This file

---

🎉 Feel free to fork, explore, or enhance the project. Contributions are welcome!
