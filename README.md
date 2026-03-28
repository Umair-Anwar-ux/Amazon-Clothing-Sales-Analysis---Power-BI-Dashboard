# Amazon-Clothing-Sales-Analysis---Power-BI-Dashboard
Overview
This project analyzes 20,000+ Amazon clothing sales records to create an interactive Power BI dashboard. The dashboard helps business stakeholders understand sales performance, discount effectiveness, customer behavior, and delivery operations across Men’s, Women’s, Kids’, and Baby categories.

Dataset
The dataset contains Amazon clothing sales records with details on products, pricing, discounts, customer demographics, payment methods, review ratings, and delivery times. Key columns include order_id, customer_id, product_name, main_category, brand, price, discount_percent, final_price, payment_method, review_rating, order_date, delivery_days, region, customer_age_group, and device_type.

Dashboard Features
Data Transformation
Data cleaning was performed to ensure quality, including handling missing values through mean, median, or mode imputation, removing duplicates and blank rows, and validating data consistency.

Data Modeling
A calendar table was created using DAX with a weekday column. A star schema was built by linking the calendar table to the sales table for time-based analysis.

Dashboard Pages

Sales Overview displays total orders, revenue, average order value, and average rating. It includes monthly and weekly revenue trends, sales by main category and region, and payment method distribution.

Product, Category & Brand Analysis shows top-selling brands by revenue, sub-category performance by quantity sold and average rating, category performance across age groups, and a summary table with orders, revenue, ratings, and customer counts.

Review & Delivery Insights covers orders by device type, age group analysis by review ratings and device preference, delivery time categorization into Fast, Medium, and Slow, and regional revenue visualization using a map chart.

Interactive Filters
Slicers allow filtering by date range, main category, region, brand, and age group for dynamic exploration.

Repository Files
amazon_sales_dashboard.pbix – Main Power BI dashboard file
amazon_clothing_sales.csv – Dataset with 20,000+ records

Skills Demonstrated
Power BI dashboard design, DAX calculations, data modeling with star schema, data cleaning and transformation, interactive visualization with slicers, and business intelligence storytelling.
