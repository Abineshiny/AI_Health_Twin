# AI_Health_Twin
 Objective:
To build a comprehensive interactive dashboard using Power BI for exploring, analyzing, and visualizing sales data — including customer behavior, profitability, trends, and geographical performance.

Dataset Used:
Source: train.csv

Contains order-level sales data with fields like:

Order Date, Sales, Customer ID, Product Category, Region, etc.

Simulated fields added: Cost, Budget, LastMovementDate, Stage, Quantity

Features Implemented by Step:

Level 1: Basic Visualizations

Sales Dashboard – Regional trends, top products using bar charts, slicers, and KPI cards.

Employee Demographics – Gender and department distribution (simulated example).

Monthly Sales Trends – Line chart with custom date table and Month-Year axis.

Top 10 Customers by Revenue – DAX with RANKX for a dynamic top 10 view.

Category-wise Sales Share – Pie and 100% stacked bar charts with slicers.

Level 2: DAX & Data Modeling
Profitability Analysis – Measures for Profit and Profit Margin using simulated cost.

YTD & YoY Growth – Time intelligence using TOTALYTD and SAMEPERIODLASTYEAR.

Sales Forecast – Line chart with forecast enabled via Analytics pane.

RFM Customer Segmentation – Columns for Recency, Frequency, Monetary, and segmentation logic.

Inventory Aging Report – Simulated LastMovementDate, with aging buckets.

Budget vs Actuals – Calculated budget, variance, and % variance with conditional formatting.

Drill-through Reports – Enable right-click navigation from summary to detail by region/product.

Dynamic KPI Switching – Slicer + DAX SWITCH() to toggle between Sales, Profit, Quantity.

Level 3: Advanced & Interactive

Sales Funnel Report – Simulated Stage column for Lead → Opportunity → Converted pipeline.

Geo Mapping with Heatmap – Location-based sales visual using map visual with color saturation.

