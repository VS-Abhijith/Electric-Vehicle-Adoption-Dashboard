# 🚗 Electric Vehicle Adoption Dashboard

### 🔗 [View Data Source](https://catalog.data.gov/dataset/electric-vehicle-population-data)

This Power BI and Flourish bar chart race project explores the rise of Electric Vehicle (EV) adoption in Washington State. 
Using data from the Washington State Department of Licensing (DOL), this dashboard offers compelling insights into the evolution of BEVs and PHEVs,
helping stakeholders make informed decisions.

---

## 📊 Project Overview
This interactive dashboard includes:
- EV adoption trends from 2000 to 2025
- Market share by brand and model
- Regional EV density (county-level and geospatial)
- EV type breakdown (BEV vs PHEV)
- Electric utility-based EV distribution
- CAFV eligibility analysis
- Dynamic filters and intuitive page navigation

---

## 📺 Supplementary Visualization (Flourish)
[🔗 View Flourish Bar Chart Race](https://public.flourish.studio/visualisation/22896671/)
![Flourish Registered Electric Vehicles by Make_ edgeA Dynamic Visualization](https://github.com/user-attachments/assets/9177a9fb-3f12-4254-a9b2-144d49508b65)


This animation showcases the rapid expansion of EVs over time. A highlight:
- **Tesla’s dominance in the early 2010s** marked a transformative shift in EV strategy.
- The bar chart captures how **innovation, incentives, and infrastructure** reshaped adoption patterns.
- Reinforces **temporal data storytelling** with engaging visuals.

---

## 🧑‍💼 Target Users
- Government agencies & policymakers
- Electric utility companies
- EV manufacturers & market analysts
- Business analysts & data scientists
- Environmental and transportation planners

---

## 🔧 Tools Used
- Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- Flourish Studio (for animated storytelling)

---

## 🧹 Data Cleaning & Preparation
| Step | Description |
|------|-------------|
| Dropped Columns | VIN, DOL, 2020 Census Tract, MSRP (incomplete) |
| Null Handling | ~3 null entries and ~7 rows missing geolocation were kept with caution |
| Location Parsing | Split `Location` POINT(x y) into `Latitude` and `Longitude` |
| Column Cleanup | Trimmed all text columns |
| Year Validation | Model years range from 2000 to 2026 |
| Derived Metrics | % BEV, % CAFV Eligibility, Total EVs per year |

---

## 📈 Visualizations
| Visualization | Type | Purpose |
|---------------|------|---------|
| EV Registration Trends | Line Chart | Adoption trends over time |
| EV Type Distribution | Donut Chart | Share of BEVs vs PHEVs |
| Top Brands & Models | Horizontal Bar Charts | Market leaders by registration count |
| EVs by County | Filled Map + Bar Chart | Identify high-penetration counties |
| CAFV Eligibility | Stacked Column Chart | Environmental eligibility status |
| Geospatial EV View | Bubble Map | EV concentration using lat/long data |
| Electric Utility View | Clustered Bar Chart | Distribution by utility provider |
| Table of Contents | Navigation Page | Interactive page switch with button |

---

## 📍 Filters & Interactivity
- Slicers available for:
  - County
  - City
  - Model Year
  - Electric Vehicle Type (BEV / PHEV)
  - Electric Utility

---

## 🧠 Key Business Insights
- **King County** tops EV registrations in the state
- **Tesla**, **Chevrolet**, and **Nissan** lead in market share
- **Post-2019 EV boom** shows the impact of government incentives and awareness
- **BEVs have higher CAFV eligibility** than PHEVs, supporting green initiatives
- **Utility-based planning** helps optimize infrastructure and grid readiness
- **Emerging EV brands like Rivian and Polestar are gaining traction**, indicating increasing competition and consumer choice in the market
- 
---

## 📦 Deployment
- Included Files:
  - `Electric Vehicle Adoption Dashboard.pbix`
  - [Flourish Bar Chart Race](https://public.flourish.studio/visualisation/22896671/)


---

## 🚀 Future Enhancements
- Integrate population data for per capita analysis
- Build predictive ML model for future EV growth
- Expand to cover all U.S. states or global adoption metrics

---

## 👨‍💻 Author
**Abhijith VS**  
IIT Madras – Diploma in Data Science  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/vsabhijith)

