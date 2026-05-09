# ⚡ India Electricity Intelligence Dashboard

A Power BI dashboard project analysing India's electricity landscape — installed generation capacity by source and state-wise consumption patterns — built using data from the Central Electricity Authority (CEA) and MNRE.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Data](https://img.shields.io/badge/Data-CEA%20%7C%20MNRE-blue?style=for-the-badge)

---

## 📊 Project Overview

This project provides an interactive Power BI report covering India's electricity sector with two core dashboards:

| Dashboard | Focus |
|---|---|
| **Dashboard 1 — Capacity** | Installed generation capacity breakdown: Solar, Wind, Hydro, Thermal, Nuclear, Bio |
| **Dashboard 2 — Consumption** | State-wise annual consumption, per capita usage, peak demand, and power availability status |

A custom **home page** acts as a navigation hub with key national KPIs — total installed capacity (467 GW), annual generation (1,824 BU), peak demand record (250 GW), and energy deficit rate (0.1%).

---

## 🗂️ Repository Structure

```
india-electricity-dashboard/
│
├── data/
│   └── India_Electricity_PowerBI_Data.xlsx   # Source data (4 sheets)
│
├── report/
│   └── India_Electricity_Dashboard.pbix      # Power BI report file
│
├── dashbord images/
│   └── Homepage.png cappacity.png consumption.png                 # dashbord  screenshot
│
└── README.md
```

---

## 📁 Data Sheets

The Excel workbook contains four sheets designed to be imported directly into Power BI:

| Sheet | Description | Key Columns |
|---|---|---|
| `National_Capacity` | All-India installed capacity by energy source | Source, Capacity_GW, Share%, Generation_BU, 2030_Target_GW |
| `State_Capacity` | State-wise capacity broken down by source | State, Region, Solar_GW, Wind_GW, Hydro_GW, Thermal_GW, RE_Share% |
| `State_Consumption` | Annual consumption and demand by state | Annual_GWh, Per_Capita_kWh, Peak_Demand_MW, Supply_Hours, Status |
| `Annual_Trend` | Year-wise national generation FY 2014–15 to 2024–25 | Thermal_BU, Solar_BU, Wind_BU, Hydro_BU, Nuclear_BU, RE_Share% |


## 📈 Key Insights

- **Maharashtra** is India's highest electricity-consuming state — 167,347 GWh/year (~10.3% of India)
- **Gujarat** leads in installed capacity (71 GW) and is the only state to have met 100% of demand every year since 2019–20
- **Solar** is the fastest-growing source — from 4.6 BU in FY 2014–15 to 144 BU in FY 2024–25 (41% CAGR)
- India's energy deficit dropped from **4.2% in 2013–14 to just 0.1% in 2024–25**
- **Kerala** is entirely import-dependent for ~75–85% of its demand despite strong hydro infrastructure (2.1 GW)
- **Bihar** has the lowest per capita consumption in India — ~350 kWh/person/year vs global average of 3,486 kWh

---

## 🛠️ How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/safvan-cheruvadi/Power-Bi-Project.git
   ```

2. Open `data/India_Electricity_PowerBI_Data.xlsx` to explore the raw dataset

3. Open `report/India_Electricity_Dashboard.pbix` in **Power BI Desktop**

4. Refresh data source path if needed:
   - Go to **Transform Data → Data Source Settings**
   - Update the Excel file path to your local clone

5. Publish to Power BI Service for sharing

---

## 📡 Data Sources

| Source | Description |
|---|---|
| [CEA](https://cea.nic.in) | Central Electricity Authority — monthly installed capacity and generation reports |
| [MNRE](https://mnre.gov.in) | Ministry of New & Renewable Energy — renewable capacity statistics |
| [MoP](https://powermin.gov.in) | Ministry of Power — year-end reviews and peak demand data |
| JMK Research | State-level renewable energy analysis |

> **Reference period:** FY 2024–25 (April 2024 – March 2025)

---



---

## 👤 Author

**Safvan**
Power BI · Data Analytics · Energy Sector

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/mohammed-safvan-e-)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://https://github.com/safvan-cheruvadi)

---

## 📄 License

This project is open source under the [MIT License](LICENSE). Data is publicly available from government sources (CEA, MNRE, MoP).

---

*Built with Power BI Desktop · Data sourced from CEA & MNRE · FY 2024-25*
