# 🍕 Pizza Sales Performance Analysis

## 📌 Business Overview
This project analyzes a year's worth of retail pizza sales data to uncover key operational insights. As a Business Analyst, the goal was to translate raw transactional data into actionable KPIs to help management optimize staffing and menu offerings.

![Dashboard Preview](dashboard_preview.png)

## 🚀 Key Performance Indicators (KPIs)
Based on the analysis of 49,000+ items sold, the following annual metrics were identified:
* **Total Revenue:** $817,860.05
* **Total Orders:** 21,350
* **Average Order Value:** $38.31
* **Average Pizzas Per Order:** 2.32

## 🔍 Key Insights & Business Recommendations
* **Peak Demand Forecasting:** Sales peak on **Fridays** (3,538 orders) and during the **12 PM - 1 PM** and **5 PM - 6 PM** windows. 
    * *Recommendation:* Increase part-time staffing during these high-volume windows to reduce order wait times.
* **Category Analysis:** **Classic** pizzas drive the highest volume (26.9% of sales), while **Large** pizzas contribute the most to revenue (45.9%).
* **Menu Optimization:** "The Classic Deluxe Pizza" is the #1 seller. Conversely, "The Brie Carre Pizza" is the lowest performer.
    * *Recommendation:* Consider a promotional bundle for underperforming "Veggie" category pizzas to balance inventory turnover.

## 🛠️ Technical Skills Demonstrated
* **Data Cleaning:** Used Power Query to handle date/time formatting and data type consistency.
* **Data Modeling:** Established relationships between order IDs and pizza categories.
* **Visualization:** Created a dynamic Executive Dashboard in Excel using Pivot Tables, Slicers, and Timeline filters.

## 📂 Data Dictionary
To ensure data integrity, the following schema was used for the analysis:

| Column Name | Description |
| :--- | :--- |
| **order_id** | Unique identifier for each order. |
| **pizza_name** | The specific name of the pizza (e.g., The Hawaiian Pizza). |
| **quantity** | Number of pizzas ordered per transaction. |
| **order_date** | The date the transaction occurred. |
| **unit_price** | Price of a single pizza. |
| **total_price** | Total cost of the order (Quantity x Unit Price). |
| **pizza_size** | Categorization by size (S, M, L, XL, XXL). |
| **pizza_category** | Grouping by type (Classic, Veggie, Supreme, Chicken). |
