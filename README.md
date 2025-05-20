# 🏘️ Tehran Housing Dashboard – Power BI

This interactive Power BI dashboard analyzes housing data from Tehran, including over 3,400 listings with detailed attributes such as price (in Rial and USD), area (m²), number of rooms, and building facilities like elevator, parking, and storage.

## 📌 Features

### 🔹 Page 1 – Overview
- Key KPI cards: 
  - Total number of listings
  - Average price (Rial)
  - Average price (USD)
- Bar chart: Top 20 most expensive districts by average price
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

## 📷 How to Export Dashboard Screenshots
1. In Power BI Desktop, go to your desired **report page** (e.g. "Overview").
2. Click anywhere outside of the visuals to **deselect**.
3. Press **Windows + Shift + S** → Select the area of the screen where the dashboard is shown.
4. Save as `dashboard_screenshot_1.png` or `dashboard_screenshot_2.png`
5. Upload these files to your GitHub repository along with the `.pbix` file.

---

🎉 Feel free to fork, explore, or enhance the project. Contributions are welcome!
