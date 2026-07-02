# E-Commerce Sales Dashboard using Power BI

## Project Overview
This project presents a comprehensive **E-Commerce Sales Dashboard** developed using **Power BI** to analyze sales performance, profit trends, customer segmentation, shipping performance, and regional distribution.

The dashboard enables interactive exploration of business metrics through dynamic filters and visualizations, helping stakeholders make data-driven decisions.

---

# Problem Statement
E-commerce companies generate large volumes of transactional data every day. Extracting meaningful insights from raw sales data is difficult without proper visualization and analysis.

The goal of this project is to transform raw e-commerce transaction data into meaningful business insights by comparing:

- YTD (Year-To-Date) Sales
- PYTD (Previous Year-To-Date) Sales
- Profit Growth
- Quantity Trends
- Regional Performance
- Customer Segment Performance

---

ecommerce-sales-dashboard-powerbi/
│
├── README.md
├── Ecommerce_Sales_Dashboard.pbix
│
├── data/
│   ├── ecommerce_data.csv
│   └── us_state_long_lat_codes.csv
│
├── screenshots/
│   ├── overview.png
│   ├── sales-by-category-segment.png
│   ├── sales-by-region.png
│   └── sales-by-shipping-type.png
│
└── docs/
    └── insights_summary.md

---    

# Objectives
- Analyze current year sales performance
- Compare YTD sales with PYTD sales
- Identify sales trends across categories
- Evaluate regional and state-level performance
- Monitor shipping type distribution
- Discover top and bottom performing products

---

# Tools & Technologies Used
- Power BI
- DAX
- Excel / CSV
- SQL
- Data Modeling
- Power Query
- Data Visualization

---

# Dataset Information

## Files Used
### 1. ecommerce_data.csv
Contains complete transaction-level e-commerce data.

Main Columns:
- Order Date
- Sales
- Profit
- Quantity
- Category
- Product Name
- Customer Segment
- Region
- State
- Ship Mode

### 2. us_state_long_lat_codes.csv
Contains geographic coordinates for state-wise visualization.

Columns:
- State
- Latitude
- Longitude

---

# Dashboard Features

## 1. KPI Cards
Dashboard tracks major KPIs:

- YTD Sales
- YTD Profit
- YTD Quantity
- YTD Profit Margin

These KPIs also compare performance against PYTD.

---

## 2. Customer Segment Analysis
Dashboard includes segment filter for:
- Consumer
- Corporate
- Home Office

This helps compare performance across customer types.

---

## 3. Sales by Category
Analyzes sales across:
- Furniture
- Office Supplies
- Technology

Metrics shown:
- YTD Sales
- PYTD Sales
- YOY Growth %
- Trend Indicator

---

## 4. Top 5 Products by Sales
Displays highest revenue-generating products.

Helps identify:
- Best sellers
- High demand products

---

## 5. Bottom 5 Products by Sales
Shows lowest performing products.

Useful for:
- Inventory optimization
- Product strategy decisions

---

## 6. Sales by Region
Regional performance comparison:
- West
- East
- Central
- South

Helps identify strongest sales regions.

---

## 7. Sales by State
Interactive map visualization to analyze:
- State-level sales distribution
- Regional clusters
- Geographic performance

---

## 8. Sales by Shipping Type
Analyzes performance across shipping modes:
- Standard Class
- Second Class
- First Class

Useful for logistics insights.

---

# Key Business Insights

## Overall Performance
- Total YTD Sales reached multi-million dollar performance
- Profit margin improved despite quantity fluctuations
- Shipping performance remained consistent

---

## Category Insights
- Office Supplies contributes highest sales
- Technology shows stable performance
- Furniture performance varies across segments

---

## Regional Insights
- West region contributes highest sales share
- East region remains second largest contributor
- South region contributes least

---

## Shipping Insights
- Standard Class dominates shipping share (~60%)
- First Class contributes lowest percentage

---

# Business Impact
This dashboard helps businesses:

- Track sales growth in real-time
- Monitor profitability
- Improve product strategy
- Optimize logistics
- Enhance business decision-making

---

# Dashboard Screenshots

## Dashboard Overview
![Overview](screenshots/overview.png)

---

## Sales by Category & Segment
![Category Segment](screenshots/sales-by-category-segment.png)

---

## Sales by Region
![Region](screenshots/sales-by-region.png)

---

## Sales by Shipping Type
![Shipping](screenshots/sales-by-shipping-type.png)

---

# How to Use
1. Download repository
2. Open `.pbix` file in Power BI Desktop
3. Load datasets if required
4. Explore dashboard using filters

---

# Future Improvements
- Real-time data integration
- Sales forecasting using Machine Learning
- Customer churn prediction
- Advanced profitability analytics

---

# Author
## Aman Sati
B.Tech CSE (AI & ML)

Interested in:
- Data Analytics
- Machine Learning
- Business Intelligence
- Power BI Development
