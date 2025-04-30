# 🚗 Electric Vehicle Adoption Dashboard

### 🔗 [View Data Source](https://catalog.data.gov/dataset/electric-vehicle-population-data)

This Power BI project explores the growth and distribution of Electric Vehicles (EVs) in Washington State, 
using publicly available registration data. The dashboard provides powerful insights that are beneficial for policymakers,
utility companies, automakers, and data science professionals.

---

## 📊 Project Overview
This dashboard provides:
- EV adoption trends from 2000 to 2025
- Market share by brand and model
- Regional EV density (county and map-based)
- Electric vehicle type breakdown (BEV vs PHEV)
- Electric utility-wise EV distribution
- CAFV eligibility metrics
- A clean, interactive user interface with filters and page navigation

---

## 🪜 Target Users
- **Government agencies & policymakers**
- **Electric utility providers**
- **EV manufacturers & stakeholders**
- **Environmental analysts**
- **Business analysts & data scientists**

---

## 🔧 Tools Used
- Power BI Desktop
- Power Query Editor
- DAX (for calculated columns and measures)

---

## 📂 Data Cleaning & Preparation
| Step | Description |
|------|-------------|
| Dropped Columns | VIN, DOL, 2020 Census Tract, MSRP (incomplete) |
| Handled Nulls | ~3 nulls and ~7 rows without geolocation retained with caution |
| Parsed Location | Split `Location` column (POINT format) into `Latitude` and `Longitude` |
| Trimmed Fields | Removed whitespaces from text fields |
| Verified Years | Model year range: 2000 to 2026 |
| Derived Metrics | % BEV, % CAFV Eligible, Total EVs per year |

---

## 🔹 Visualizations
| Visualization | Type | Purpose |
|---------------|------|---------|
| EV Registrations Over Time | Line Chart | Adoption trends across years |
| EV Type Breakdown | Donut Chart | BEV vs PHEV proportions |
| Top 5 Brands / Models | Horizontal Bar Chart | Most registered makes and models |
| EVs by County | Filled Map + line chart | Regional penetration analysis |
| CAFV Eligibility | Stacked Column Chart | Share of environmentally eligible vehicles |
| Geospatial View | Bubble Map | EV clusters using lat/long |
| TOC Page | Buttons & Navigation | Improve user experience |


![image](https://github.com/user-attachments/assets/9fb021be-bb34-44f5-9fb0-02bd1e49d46f)

---



## 📈 Key Insights
- **Clark County** leads in EV registrations
- **Tesla**, **Chevy**, and **Nissan** dominate the market
- **EV adoption surged post-2019**, indicating rising interest and possible policy impacts
- **High CAFV eligibility** rate for BEVs vs moderate for PHEVs
- **Utility-level trends** can help optimize EV infrastructure planning

---

## 📍 Deployment
- Power BI `.pbix` file is included in this repo
- Dashboard includes slicers for:
  - County
  - City
  - Electric Vehicle Type
  - Model Year
  - Electric Utility

---

## 📅 Future Improvements
- Merge with population/census data for per capita analysis
- Predictive model for next 5 years of EV growth
- Expand scope to national or multi-state data

---

## 🌟 Author
**Abhijith VS**  
IIT Madras - Diploma in Data Science  
[LinkedIn Profile] (www.linkedin.com/in/vsabhijith)

