# 🌍 Advanced Tableau Storytelling & Interactive Analytics

Interactive Tableau dashboards and a data story analyzing economic, demographic, and public health indicators across 200+ countries.

## 📌 Overview
A research organization needs to understand how wealth, health, and demographics relate globally. This project cleans the Country Data Comparison dataset and presents the findings through three linked dashboards and one Tableau Story.

## 📊 Dashboards
| Dashboard | Focus |
|---|---|
| **Overview** | Global map, top-N countries, life expectancy distribution, infant mortality by income group |
| **Economy** | Inflation alerts, growth, trade balance, wealth vs. life expectancy, anomalies |
| **Demographics** | Population treemap, birth rate, internet penetration, natural increase |

## 🛠️ Features
- **7 visualization types:** Map, Bar, Histogram, Box Plot, Scatter + Trend Line, Treemap, Heatmap
- **6 parameters:** Indicator, Number of Countries, High-Income Cutoff, Middle-Income Cutoff, Inflation Alert Level, Selected Country
- **8 dashboard actions:** 3 parameters, 2 filters, 3 highlights
- **Calculated fields:** Income Group, Top-N flag, selected metric, KPIs, alert flags
- **Navigation:** Cross-dashboard buttons and a global Income Group filter
- **Tableau Story:** 5 story points, one message each

## 🔍 Key Findings
- **Correlations:** GDP per capita vs. infant mortality = **-0.86**; vs. life expectancy = **+0.81**; vs. GDP growth ≈ **-0.09**
- **Demographics:** Birth rate is **12.15** (high income) vs. **30.98** (low income)
- **Digital divide:** Internet penetration is **40.27%** vs. **2.50%**
- **Anomalies:** Zimbabwe (133% inflation), Iraq (52.3% growth), Chad (38%)

## 📁 Repository Structure
├── data/
│ └── Country_Clean.xlsx
├── tableau/
│ └── Tableau_Packaged_Workbook.twb
├── docs/
│ └── Project_Documentation.pdf
├── screenshots/
│ ├── dashboard1_overview.png
│ ├── dashboard2_economy.png
│ ├── dashboard3_demographics.png
│ └── story.png
└── README.md

## ▶️ How to Use
1. Download the repository.
2. Open `Tableau_Packaged_Workbook.twb` in Tableau Desktop or Tableau Public.
3. If the data source is not found, re-point it to `data/Country_Clean.xlsx`.
