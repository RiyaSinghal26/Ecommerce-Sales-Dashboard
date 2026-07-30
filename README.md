# 🛒 E-Commerce Sales Performance Dashboard (Power BI)

An end-to-end interactive Power BI Analytics Solution designed to analyze Year-to-Date (YTD) sales metrics, monitor YoY revenue trends, track regional distributions, and identify top/bottom performing product lines for strategic decision-making.

---

## 📌 Executive Summary & Business Problem

E-commerce businesses require real-time visibility into key performance indicators (KPIs) to drive profitability, optimize inventory, and improve customer segment targeting. 

This project solves this challenge by transforming raw transaction data into a dynamic dashboard that tracks:
* **Current Year vs. Prior Year Performance:** Tracking YTD vs. PYTD sales and profit margins.
* **Geographical Sales Intensity:** Visualizing state-level revenue trends across the United States.
* **Product Line Optimization:** Isolating top 5 revenue-generating items and bottom 5 underperforming items.
* **Customer Segment Analysis:** Segmenting behavior across *Consumer*, *Corporate*, and *Home Office* categories.

---

## 📊 Key Dashboard Features & Metrics

### 1. Advanced Dynamic KPI Cards
* **YTD Sales:** $11.53M (with YoY percentage growth indicator & trend ribbon)
* **YTD Profit:** $1.34M (with YoY growth indicator)
* **YTD Quantity Sold:** #107.2K units
* **YTD Profit Margin:** 11.58%
> *Dynamic Conditional Formatting:* Metric indicators automatically shift background colors (Green for growth, Red for decline) based on YoY trends.

### 2. Category & Performance Matrix
* Interactive table breaking down **YTD Sales**, **PYTD Sales**, and **YoY Growth %** across product categories (*Office Supplies*, *Furniture*, *Technology*).

### 3. Spatial & Regional Insights
* **Geographical Map:** Bubble chart mapping US state-level sales performance.
* **Regional & Shipping Breakdown:** Donut visual analyzing distribution across Regions (*West*, *East*, *Central*, *South*) and Shipping Modes (*Standard Class*, *Second Class*, *First Class*, *Same Day*).

### 4. Product Level Drill-Down
* Horizontal bar charts rendering the **Top 5 Products** by revenue alongside the **Bottom 5 Products** to support inventory management.

---

## 📁 Repository Structure

```text
Ecommerce-Sales-Dashboard/
│
├── Dashboard.pbix                 # Power BI Master File
├── ecommerce_data_excel.xlsx      # E-commerce Sales Transaction Dataset
├── us_state_long_lat_codes.csv    # Spatial Geocoding Dataset
└── README.md                       # Documentation Page
'''
##🛠️ Tech Stack
Business Intelligence: Microsoft Power BI Desktop
Data Transformation: Power Query & DAX (Data Analysis Expressions)
Database / Sources: CSV / Excel Dataset
Data Modeling: Star Schema Design
