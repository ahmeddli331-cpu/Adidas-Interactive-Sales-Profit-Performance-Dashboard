# Adidas US Interactive Sales & Profit Performance Dashboard

A comprehensive, interactive business intelligence dashboard built in Microsoft Excel to monitor, analyze, and optimize Adidas sales performance, profitability trends, and regional distribution across a multi-year timeline (2023–2025). 

This project transforms raw transactional data into actionable operational insights, allowing stakeholders to drill down into specific regional metrics, customer demographics, product-level profit margins, and preferred payment methods.

---

## 📊 Dashboard Overview & Visual Architecture

The dashboard is structured into six key visual modules and interactive control panels, designed for seamless navigation and rapid executive reporting:

1. **KPI Highlights (Top Right):** Displays the macro performance indicator — **Total Sales ($287,378)**.
2. **Total Sales Per Category (Donut Chart):** Breaks down revenue by primary product divisions:
   * **Footwear:** 62% (Dominant revenue driver)
   * **Apparel:** 27%
   * **Accessories:** 11%
3. **Total Sales Per Gender (Bar Chart):** Compares sales volume across **Female**, **Male**, and **Other** customer segments, indicating market penetration.
4. **Total Sales Per Region (Donut Chart):** Visualizes geographical revenue distribution across key territories:
   * **Egypt:** 30%
   * **Iraq:** 28%
   * **Oman:** 24%
   * **KSA:** 12%
   * **Lebanon:** 6%
5. **Total Sales By Date (Line Chart):** Captures the longitudinal sales trajectory from **Q1 2023 through Q3 2025**, highlighting seasonal peaks (such as Q4 2023 at $31,322.27) and cyclical fluctuations.
6. **Total Profit Per Product (Horizontal Bar Chart):** Ranks individual product lines by net profitability, distinguishing top-tier margin contributors (e.g., *Predator Freak* at $9,218.42 and *Ultraboost Light* at $8,876.32) from baseline items.

---

## 🎛️ Interactive Elements & Filtering (Slicers)

The dashboard utilizes advanced Excel Slicers to provide cross-filtering capabilities. Selecting any criteria instantly recalibrates all charts, metrics, and totals:

* **Payment Method Slicer:** Filters data by transaction types including *Apple Pay, Cash, Credit Card, Debit Card, Google Pay, NetBanking, PayPal, and UPI*.
* **Region Slicer:** Isolates performance data for specific countries (*Egypt, Iraq, KSA, Lebanon, Oman*).

---

## 📈 Dashboard Overview
<img width="1720" height="696" alt="Screenshot 2026-06-05 001542" src="https://github.com/user-attachments/assets/e8bd5b6e-d9d3-46f7-97fd-1cf04482c32b" />

---

## 📈 Key Insights & Business Intelligence

Based on the dashboard state, several high-level strategic takeaways can be formulated:
* **Product Strategy:** Footwear is the core business pillar, accounting for nearly two-thirds of total revenue.
* **Profitability Champions:** *Predator Freak* and *Ultraboost Light* generate the highest absolute profits, suggesting marketing spend should be heavily allocated toward these lines.
* **Geographic Focus:** Egypt and Iraq represent the strongest markets (combining for 58% of total sales), whereas Lebanon holds significant room for market expansion or localized promotional interventions.

---

## 🛠️ Technical Specifications & Features

* **Platform:** Microsoft Excel (Advanced Data Modeling & Charting)
* **Visual Components:** Custom styled Donut charts, clustered column charts, smoothed line charts, and conditioned horizontal bar charts.
* **Layout Design:** Unified mint-green theme with dark modern headers, designed to prevent visual fatigue during extended review sessions.
* **Data Refreshability:** Configured to automatically update all charts upon modifications to the underlying transactional data sheets.

---

## 🚀 How to Use the Dashboard

1. Open the `.xlsx` file in Microsoft Excel (2019 or newer recommended for optimal slicer formatting).
2. Ensure macros/content are enabled if prompted to allow full interactive functionality.
3. Use the **Payment Method** or **Region** slicers on the right side to filter the data. Hold `Ctrl` to select multiple fields simultaneously.
4. Click the **Clear Filter** icon at the top right of any slicer to reset the view to aggregate totals.
