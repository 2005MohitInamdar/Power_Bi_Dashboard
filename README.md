# Power_Bi_Dashboard


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. **Comprehensive Business Performance Dashboard**

A fully-interactive Power BI dashboard designed to provide insights into overall business performance, including sales, profit, discounts, category trends, and time-based analysis. This report helps decision-makers quickly identify key patterns, track KPIs, and optimize operations using real-time analytics.

This dashboard consolidates multiple business metrics into a single, easy-to-navigate interface. It highlights performance across cities, product categories, and time periods, enabling data-driven decision-making for sales teams, finance teams, and business managers.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2. **Purpose of the Dashboard**
   
This dashboard was designed to deliver a clear and interactive overview of overall business performance by focusing on the following objectives:
Summarize the organization’s overall business health using key visual metrics.
Track and analyze core KPIs including Sales, Profit, and Quantity.
Identify top-performing cities, categories, and product types to support data-driven decision-making.
Analyze the impact of discounts on profitability and highlight areas for margin optimization.
Visualize time-based profit trends to support forecasting and strategic planning.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
3. **Tech Stack**
   
🔹 Power BI Desktop
Used as the main platform to build the entire dashboard — for modeling, cleaning, designing visuals, and publishing.

📊 DAX (Data Analysis Expressions)

Used to create KPIs and calculated measures like Total Sales, Total Profit, Profit Ratio, etc.
DAX helps convert raw numbers into meaningful insights.

🧹 Power Query (M Language)

Used to clean, format, and transform the raw dataset (removing nulls, fixing data types, renaming columns, etc).
This ensures the data model is accurate before building visuals.

🗂️ Data Modeling

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


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4. **Dataset**

The dashboard uses the **Superstore Sales Dataset**, a popular sample dataset available on Kaggle.
It contains historical sales data for a fictional retail company, including fields such as Order ID, Customer Name, Product Category, Sub-Category, Sales, Profit, Quantity, Discount, Region, and Order Date.

This dataset was chosen for its rich KPIs, multiple dimensions, and suitability for analyzing sales trends, profits, and top-performing products. Data preprocessing included removing nulls and duplicates, standardizing column names, and converting date fields to proper types for modeling and visualization in Power BI.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

5. **Dashboard Features / Highlights**

detailed overview of the key visualizations in the Power BI Business Performance Dashboard.


📌 KPI Cards — Total Sales, Total Profit & Total Quantity

Purpose: Quickly monitor the overall financial health of the business.

KPIs:

💰 Total Sales: ₹2.3M — cumulative revenue across all products and regions.

📈 Total Profit: ₹286.4K — profit after deducting costs.

📦 Total Quantity: 38K — total units sold across all categories.


📌 Sales & Profit by City (Bar & Column Combo Chart)

Purpose: Identify regional performance differences and improvement opportunities.

Insights:

Sales bars show revenue by city (New York, Los Angeles, Seattle, San Francisco).

Profit bars indicate profitability of each location.

Highlights which cities drive high revenue and which need attention.


📌 Discount by Category (Donut Chart)

Purpose: Understand discount allocation and its impact on profit.

Insights:

Office Supplies – 60.71% of discounts

Furniture – 23.63%

Technology – 15.66%

Shows which categories receive the most discounts and potential effect on margins.


📌 Profit Over Time (Line Chart)

Purpose: Monitor profit fluctuations to support forecasting and strategic planning.

Insights:

Peaks: April, August, December

Dips: July, October

Detects seasonality and operational inefficiencies.


📌 Profit by Discount (Scatter/Trend Chart)

Purpose: Evaluate if discounts drive sales effectively or hurt profitability.

Insights:

Negative correlation at high discount levels.

Sharp profit drops when discounts exceed certain thresholds.


📌 Percentage of Units Sold per Category (Pie Chart)

Purpose: Understand customer buying behavior and stock movement.

Insights:

Office Supplies – 60.48%

Furniture – 21.2%

Technology – 18.32%

Highlights dominant product categories and contribution to sales volume.


📌 Product Category Sales vs Profit (Bar Chart)

Purpose: Spot high-revenue but low-profit products and optimize pricing/cost.

Insights:

Phones: High revenue, moderate profit

Tables: Moderate revenue, low/negative profit

Paper & Supplies: Smaller sales contribution


📌 Year Selector (Slicer)

Purpose: Enable dynamic, time-based filtering to compare performance across 2014–2017.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

❓ **Key Questions This Dashboard Answers**

* What are the overall business performance metrics?

Total Sales

Total Profit

Total Quantity Sold
The KPI cards instantly summarize the company's financial health.


* Which cities contribute the most to sales and profit?

The city-wise comparison highlights:

Top-performing markets

Low-performing cities

Revenue vs. profit discrepancies across regions


* How are discounts distributed across product categories?

The discount donut chart answers:

Which categories receive the highest/lowest discounts

Whether discount strategies are consistent or skewed


* How does profit change over time throughout the year?

The monthly line chart reveals:

Seasonal trends

Profit spikes or dips

Best and worst months

Impact of periodic promotions or events


* Is there a relationship between discounts and profitability?

The Profit vs Discount chart answers:

Whether higher discounts reduce profit

Which discount ranges produce optimal profit

Signs of over-discounting that harm margins


* Which product categories drive the highest volume of sales?

The units sold pie chart shows:

Dominant categories in terms of volume

How category demand varies

Which categories need inventory prioritization


* Which product types generate the most revenue and profit?

The product-wise sales and profit chart answers:

Best-selling products

Products with high revenue but low profit

Loss-making product categories

Opportunities for pricing or cost improvements


* How does performance vary by year?

The year slicer enables:

Multi-year comparison

Trend analysis

Identification of yearly growth or decline


* Where are the major opportunities for business improvement?

From the visuals, the dashboard helps identify:

Unprofitable products

Over-discounted categories

Underperforming cities

Seasonal low points

Inventory planning opportunities


* What are the key drivers of sales vs. profit in the business?

The combined insights reveal:

Whether quantity, pricing, discounting, or geography drive results

How category mix influences profit

Where operational focus should shift

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Repository Structure / Files**


<img width="293" height="170" alt="image" src="https://github.com/user-attachments/assets/d6a6adc0-7d07-4123-b0cb-c703bc803898" />


