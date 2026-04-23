# Basic-Details-of-Indian-Schools
A data analysis project on Indian schools covering geographic distribution, school categories, and infrastructure insights using MS Excel and Power BI.
# 📚 Basic Details of Indian Schools — Data Analysis Project

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat)

> A comprehensive data analysis project exploring the geographic distribution, school categories, management types, and infrastructure status of Indian schools using **Microsoft Excel** and **Power BI**.

---

## 📌 Project Overview

India has one of the largest school education systems in the world. This project dives into a dataset of Indian schools to uncover patterns in:

- **Geographic distribution** across states and districts
- **School categories** (Primary, Upper Primary, Secondary, Higher Secondary)
- **Management types** (Government, Private, Aided, etc.)
- **Infrastructure availability** (electricity, toilets, drinking water, libraries, etc.)
- **Medium of instruction** across regions

The goal is to derive actionable insights that can help educators, policy makers, and researchers understand the state of school education across India.

---

## 🗂️ Dataset

| Field | Description |
|---|---|
| **Source** | [Unified District Information System for Education (UDISE)](https://udiseplus.gov.in/) / Open Government Data |
| **Format** | `.csv` / `.xlsx` |
| **Records** | 10,000+ school entries |
| **Coverage** | Multiple states and union territories across India |

### Key Columns

- `School_Name` — Name of the school
- `State` / `District` — Geographic location
- `School_Category` — Primary / Upper Primary / Secondary / Higher Secondary
- `School_Management` — Government / Private / Aided / Unaided
- `Medium_of_Instruction` — Hindi / English / Tamil / etc.
- `Total_Students` — Enrolled student count
- `Total_Teachers` — Teaching staff count
- `Electricity_Available` — Yes / No
- `Drinking_Water_Available` — Yes / No
- `Toilet_Available` — Yes / No
- `Library_Available` — Yes / No
- `Computer_Lab` — Yes / No

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data cleaning, transformation, pivot tables, basic charts |
| **Power BI** | Interactive dashboards, advanced visualizations, DAX measures |

---

## 🔍 Analysis Performed

### 1. 🌍 Geographic Distribution
- State-wise and district-wise school count
- Heatmap of school density across India
- Top 10 states by number of schools

### 2. 🏫 School Category Breakdown
- Distribution of Primary, Upper Primary, Secondary, and Higher Secondary schools
- Category-wise enrollment trends
- Category vs. management type cross-analysis

### 3. 🏛️ Management Type Analysis
- Government vs. private school ratio
- State-wise dominance of management types
- Management type vs. infrastructure availability

### 4. 🏗️ Infrastructure Insights
- % of schools with electricity, water, toilets, libraries, and computer labs
- State-level infrastructure gap analysis
- Infrastructure availability vs. school category

### 5. 📖 Medium of Instruction
- Language-wise school distribution
- Regional language preferences across states

---

## 📊 Dashboard Highlights (Power BI)

- **KPI Cards** — Total schools, total students, total teachers, avg. student-teacher ratio
- **Geo Map** — State-wise school distribution on India map
- **Bar/Column Charts** — Category and management type comparisons
- **Donut Charts** — Infrastructure availability percentages
- **Slicers/Filters** — Dynamic filtering by state, category, management, and medium

---

## 📁 Project Structure
Basic-Details-of-Indian-Schools/
│
├── 📂 data/
│   ├── raw_data.csv                  # Original dataset
│   └── cleaned_data.xlsx             # Cleaned and transformed data
│
├── 📂 excel-analysis/
│   └── Indian_Schools_Analysis.xlsx  # Excel workbook with pivots & charts
│
├── 📂 powerbi/
│   └── Indian_Schools_Dashboard.pbix # Power BI dashboard file
│
├── 📂 screenshots/
│   ├── dashboard_overview.png
│   ├── geographic_map.png
│   ├── infrastructure_analysis.png
│   └── category_breakdown.png
