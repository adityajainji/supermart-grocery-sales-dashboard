
# 🛒 Supermart Grocery Sales Dashboard — Excel

**Created by:** Aditya Jain

An interactive Excel dashboard built to analyze grocery sales, profitability, product performance, discount patterns, and geographic trends using PivotTables, PivotCharts, and slicers.

## 📌 Project Overview

This project analyzes **9,994 grocery order records from 2015 to 2018** to identify business trends, understand profitability, and support data-driven decision-making.

### 🛠️ Tools & Technologies

- Microsoft Excel
- Excel Tables and PivotTables
- PivotCharts
- Slicers and Report Connections
- Calculated fields and helper columns
- Combo charts with secondary axes
- Conditional formatting and KPI cards

## 🎯 Business Objectives

1. **Overall Sales Performance** — Analyze sales and profit trends across years.
2. **Product Performance** — Compare category and sub-category sales and profitability.
3. **Profit & Discount Analysis** — Investigate profit margins and performance across discount bands.
4. **Geographic Performance** — Compare sales and profitability across regions and cities.

## 🖼️ Dashboard Preview

### Executive Dashboard

The following four screenshots show different sections of the same dashboard.

![Executive Dashboard - Part 1](images/dashboard_1.png)

![Executive Dashboard - Part 2](images/dashboard_2.png)

![Executive Dashboard - Part 3](images/dashboard_3.png)

![Executive Dashboard - Part 4](images/dashboard_4.png)

## 📊 Business Analysis

### Objective 1 — Overall Sales Performance

![Overall Sales Performance](images/objective_1.png)

### Objective 2 — Product Performance

![Product Performance](images/objective_2.png)

### Objective 3 — Profit & Discount Analysis

![Profit and Discount Analysis](images/objective_3.png)

### Objective 4 — Geographic Performance

![Geographic Performance](images/objective_4.png)

## 📁 Dataset Preview

![Dataset Preview](images/dataset.png)

## 🔍 Key Insights

### 1. Overall Sales Performance

- Total sales were approximately **₹1.50 crore**.
- Total profit was approximately **₹37.47 lakh**.
- Overall profit margin was approximately **25.05%**.
- Annual sales increased from approximately **₹29.76 lakh in 2015** to **₹49.78 lakh in 2018**, an increase of around 67%.
- Annual sales growth was approximately 5.3% in 2016, 23.6% in 2017, and 28.6% in 2018.

### 2. Product Performance

- The seven product categories each contributed approximately 13.6%–15.2% of total sales.
- Health Drinks generated approximately **₹10.51 lakh** in sales, while Soft Drinks generated approximately **₹10.34 lakh**.
- Snacks and Eggs, Meat & Fish recorded the highest category profits, at approximately ₹5.7 lakh each.
- Oil & Masala recorded the lowest category profit, at approximately ₹4.98 lakh.
- Soft Drinks, Cookies, Masalas, Cakes, Biscuits, and Spices had above-average sales but below-average profit margins.

### 3. Profit & Discount Analysis

- Average profit per order remained approximately ₹373–₹380 across the analyzed discount bands.
- The analysis did not show a clear relationship between discount bands and average profit per order.
- Sub-category profit margins ranged from approximately 23.8% to 26.3%.

### 4. Geographic Performance

- The dataset contains records from Tamil Nadu only, so meaningful state-level comparisons are not possible.
- The West and East regions together contributed approximately 60% of sales and profit.
- Kanyakumari generated approximately **₹7.07 lakh** in sales, accounting for around 4.7% of total sales.
- The top 10 cities contributed approximately 44% of sales.
- Kanyakumari, Tirunelveli, Salem, Tenkasi, Coimbatore, and Cumbum recorded above-average sales but below-average profit margins.

## ⚠️ Data Notes & Limitations

- **Single-state dataset:** All records are from Tamil Nadu; the analysis therefore focuses on city- and region-level comparisons.
- **North region anomaly:** The North region contains only one record, with sales of approximately ₹1,254. This may be an anomaly and was excluded from the main regional conclusions.
- **Discount analysis:** All discounts fall between 10% and 35%. The observed relationship may reflect limitations in the dataset rather than a general business rule.
- **Product-level analysis:** The dataset does not contain individual product names, so product analysis is performed at the sub-category level.
- **Static insight captions:** Some written dashboard insights do not automatically change when slicers are used.
- **Profit margin:** Calculated as total profit divided by total sales.
- **High sales, low margin:** Defined as above-average sales combined with below-average profit margin.

## 🎛️ Dashboard Interactivity

The dashboard includes slicers for:

- **Year**
- **Region**
- **Category**

These filters allow users to explore performance across different time periods, geographic regions, and product categories.

## 📂 Repository Structure

```text
supermart-grocery-sales-dashboard/
│
├── README.md
├── Supermart_Grocery_Sales_Dashboard.xlsx
│
└── images/
    ├── dashboard_1.png
    ├── dashboard_2.png
    ├── dashboard_3.png
    ├── dashboard_4.png
    ├── objective_1.png
    ├── objective_2.png
    ├── objective_3.png
    ├── objective_4.png
    └── dataset.png
```
## 📚 Data Source

The dataset used in this project was provided by **SapphireIQ** as part of a data analytics student project. All analysis, pivot tables, charts and dashboard design are my own work.

## 👤 Author

**Aditya Jain**

GitHub: [@adityajainji](https://github.com/adityajainji)

---

*Developed using Microsoft Excel for interactive sales and profitability analysis.*
