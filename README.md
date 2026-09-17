<div align="center">

# 📊 India Digital Payments Dashboard

### UPI Transaction Trends & Payment Analytics | 2020–2026

**Interactive Power BI dashboard built using official Reserve Bank of India data** 🇮🇳

</div>

---

## 🚀 Project Overview

This project analyzes the growth and changing patterns of India's digital payment ecosystem using **25,668 records from official RBI data** covering **June 2020 to April 2026**.

The dashboard focuses on UPI transaction volume, transaction value, yearly growth, peak-day activity, market share, and comparisons with other major payment modes such as **NEFT and IMPS**.

The goal is to turn raw financial data into an interactive and easy-to-understand **data storytelling dashboard**.

---

## 🎯 Objectives

- Analyze long-term UPI transaction growth
- Compare UPI with other digital payment modes
- Track transaction volume and transaction value
- Calculate year-over-year growth
- Identify peak transaction activity
- Analyze UPI's share of digital payments
- Provide interactive filtering for exploratory analysis

---

## 📸 Dashboard Preview

> Dashboard screenshots can be added here as the repository is expanded.

### Main Dashboard

![India Digital Payments Dashboard](screenshots/dashboard.png)

### Growth Analysis

![UPI Growth Analysis](screenshots/growth-analysis.png)

---

## 📈 Dashboard Highlights

### KPI Cards

The dashboard provides high-level KPIs for:

- **Total UPI Volume:** 7.15M
- **Total UPI Value:** 104.50M
- **Peak Day Volume:** 8.02K
- **UPI Market Share:** 81.26%

### Interactive Filters

Users can filter the dashboard by:

- 📅 Year
- 📆 Quarter
- 💳 Payment Mode

---

## 📊 Visual Analysis

### UPI Monthly / Yearly Volume Trend

Tracks the change in UPI transaction volume over time and highlights the rapid expansion of digital payments.

### Year-wise UPI Growth

Compares UPI volume across years and makes the growth trajectory easier to interpret.

### Payment Mode Share

Shows the relative contribution of different payment modes including UPI, NEFT, IMPS, BBPS, NACH and other modes present in the RBI dataset.

### UPI vs NEFT vs IMPS

Provides a comparative view of transaction volumes across major digital payment channels.

---

## 🔎 Key Insights

Based on the dashboard analysis:

- UPI volume increased substantially between 2020 and 2025.
- The dashboard records **22.83 Lakh Crore** of UPI volume in 2025 based on the analyzed dataset.
- UPI represents approximately **81.26%** of the digital payment volume represented in the dashboard's market-share calculation.
- Peak-day activity reached approximately **8,016 Lakh transactions** in March 2026 according to the dashboard analysis.
- The dashboard enables year-over-year comparison to identify changing growth patterns.

> Values and percentages above reflect the project's analyzed RBI dataset and dashboard calculations.

---

## 🧹 Data Preparation

Raw RBI data was transformed before visualization using **Power Query**.

```text
Raw RBI Dataset
      ↓
Data Import
      ↓
Data Cleaning
      ↓
Data Type Transformation
      ↓
Column Preparation
      ↓
Data Modeling
      ↓
DAX Measures
      ↓
Interactive Dashboard
```

The preparation workflow focused on creating analysis-ready fields for time-based and payment-mode comparisons.

---

## 🧮 DAX Analysis

DAX was used to create calculated measures for dashboard KPIs and trend analysis, including:

- Total transaction volume
- Total transaction value
- Year-over-year growth
- Peak-day volume
- Payment-mode share
- Comparative payment-mode analysis

This allowed the dashboard to move beyond static charts and provide dynamic calculations through user-selected filters.

---

## 🛠️ Technology Stack

| Category | Tools |
|---|---|
| BI Platform | Power BI Desktop |
| Data Transformation | Power Query |
| Analytics | DAX |
| Data Source | Reserve Bank of India (RBI) |
| Visualization | Power BI Charts & KPI Cards |
| Analysis | Data Cleaning, Trend Analysis, Comparative Analysis |

---

## 📁 Repository Structure

```text
UPI-Digital-Payments-Analysis/
│
├── Dashboard_project.pbix
├── screenshots/
│   ├── dashboard.png
│   └── growth-analysis.png
└── README.md
```

The `.pbix` file contains the Power BI dashboard, data model, transformations, visuals, and DAX calculations used for the project.

---

## 💡 What I Learned

Through this project, I practiced:

- Building an end-to-end BI dashboard from raw data
- Data cleaning and transformation using Power Query
- Writing DAX measures for analytical KPIs
- Year-over-year growth analysis
- Designing interactive dashboards
- Data storytelling using government datasets
- Converting business questions into visual analytics

---

## 📌 Project Scope

This project is primarily focused on **descriptive and exploratory analytics**. It helps users understand historical payment trends and patterns rather than predicting future transaction volumes.

---

## 👨‍💻 Author

**Aniket Raj**

B.Tech Computer Science & Engineering

- GitHub: [Aniketrajjj](https://github.com/Aniketrajjj)

---

<div align="center">

### 🇮🇳 Data → Analysis → Visualization → Insight

**Built with Power BI, DAX & RBI Data** 📊

</div>
