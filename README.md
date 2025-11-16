# Power_Bi_Dashboard

1. Comprehensive Business Performance Dashboard

A fully-interactive Power BI dashboard designed to provide insights into overall business performance, including sales, profit, discounts, category trends, and time-based analysis. This report helps decision-makers quickly identify key patterns, track KPIs, and optimize operations using real-time analytics.

This dashboard consolidates multiple business metrics into a single, easy-to-navigate interface. It highlights performance across cities, product categories, and time periods, enabling data-driven decision-making for sales teams, finance teams, and business managers.

2. Purpose of the Dashboard
This dashboard was designed to deliver a clear and interactive overview of overall business performance by focusing on the following objectives:
Summarize the organization’s overall business health using key visual metrics.
Track and analyze core KPIs including Sales, Profit, and Quantity.
Identify top-performing cities, categories, and product types to support data-driven decision-making.
Analyze the impact of discounts on profitability and highlight areas for margin optimization.
Visualize time-based profit trends to support forecasting and strategic planning.

3. Tech Stack
🔹 Power BI Desktop
Used as the main platform to build the entire dashboard — for modeling, cleaning, designing visuals, and publishing.

📊 DAX (Data Analysis Expressions)
Used to create KPIs and calculated measures like Total Sales, Total Profit, Profit Ratio, etc.
DAX helps convert raw numbers into meaningful insights.

🧹 Power Query (M Language)
Used to clean, format, and transform the raw dataset (removing nulls, fixing data types, renaming columns, etc).
This ensures the data model is accurate before building visuals.

🗂️ Data Modeling (Star Schema)
Used to structure data into related tables (Fact + Dimensions).
This improves performance, avoids redundancy, and makes calculations faster and more accurate.

📈 Power BI Visualizations
Used to visually represent insights using:
📇 Cards
🍩 Donut charts
📦 Bar charts
📊 Column charts
📉 Line charts
🥧 Pie charts
Each visual helps highlight trends, comparisons, and insights in a clear, interactive format.

📂 Dataset
The dashboard uses the **Superstore Sales Dataset**, a popular sample dataset available on Kaggle.
It contains historical sales data for a fictional retail company, including fields such as Order ID, Customer Name, Product Category, Sub-Category, Sales, Profit, Quantity, Discount, Region, and Order Date.

This dataset was chosen for its rich KPIs, multiple dimensions, and suitability for analyzing sales trends, profits, and top-performing products. Data preprocessing included removing nulls and duplicates, standardizing column names, and converting date fields to proper types for modeling and visualization in Power BI.

