# Coke-Sales-Analysis

**Project Overview**

This project delivers a comprehensive analysis of Coca-Cola’s 2021 sales performance across key American retailers. The goal was to transform raw transactional data into actionable business intelligence using Microsoft Excel.

The project follows the full data analysis lifecycle:

Data Preparation: Cleaning and standardizing raw data for consistency.

Exploratory Data Analysis (EDA): Using PivotTables and Excel formulas to identify performance trends.

Profitability Insights: Investigating the interplay between pricing, sales volume, and operating margins.

Dashboarding: Building an interactive Excel dashboard with slicers for intuitive exploration.

The end result is a data-driven evaluation of Coca-Cola’s retail strategy, highlighting both areas of strength and opportunities for growth.

**Dataset**

The analysis is based on a transactional dataset (Data.csv) representing Coca-Cola’s U.S. beverage sales in 2021.

Key fields in the dataset include:

Retailer: Name of the retail company (e.g., Sodapop, BevCo).

Region, State, City: Geographic attributes for sales transactions.

Beverage Brand: Product sold (e.g., Coca-Cola, Diet Coke, Powerade, Dasani).

Price per Unit: Unit price of the beverage.

Units Sold: Quantity sold per transaction.

Total Sales ($): Revenue from sales.

Operating Profit ($): Profit earned from transactions.

Operating Margin (%): Profitability ratio = Operating Profit ÷ Total Sales.

**Project Objectives**

This project aimed to answer three key business questions:

Performance Analysis: How do Coca-Cola’s sales vary by retailer, region, and over time (monthly)?

Profitability Insights: What is the relationship between product pricing, sales volume, and overall profitability?

Margin Trends: How do operating margins evolve across different retailers and markets, and what do they reveal about opportunities for optimization?

**Tools & Methods**

Microsoft Excel (Core Tool)

Data Cleaning & Preparation: Standardized headers, ensured consistent formats, converted ranges to Excel Tables.

PivotTables & PivotCharts: For aggregation and multidimensional analysis.

Excel Formulas: Derived fields such as Price per Unit and calculated profitability metrics.

Data Visualization: Bar charts, line graphs, scatter plots, and map charts.

Dashboarding & Slicers: Built an interactive dashboard for stakeholder exploration.

**Analytical Process**

1. Data Preparation

Loaded raw Data.csv into Excel.

Cleaned noisy headers and standardized column names.

Verified data types for dates, currency values, and percentages.

Converted the dataset into an Excel Table (tbl_sales) for dynamic referencing.

Added derived metrics:

Price per Unit = Total Sales ÷ Units Sold

Operating Margin % = Operating Profit ÷ Total Sales

2. Exploratory Data Analysis (EDA)

Four key PivotTables were created to explore performance:

Retailer Analysis: Total Sales & Operating Profit by Retailer.

Regional Analysis: Sales contribution by Region.

Brand Analysis: Sales share by Beverage Brand.

Time Analysis: Monthly sales to identify seasonality.

3. Profitability Analysis

Built a scatter plot comparing Average Price per Unit vs. Average Operating Margin across retailers.

Observed distinct business strategies:

Some retailers (e.g., Sodapop) maintain premium pricing with high margins.

Others (e.g., BevCo) rely on low price, high volume strategies that compress profitability.

4. Dashboard Creation

Consolidated visuals into a single Dashboard sheet.

Included:

Bar chart: Sales & Profit by Retailer

Line chart: Monthly Sales Trend

Heatmap: Regional Sales Distribution

Pie chart: Brand Contribution

Added interactive slicers for Region and Beverage Brand to allow users to filter dynamically.

**Key Insights**

**Top Performers:**

Sodapop generated the highest revenue.

Northeast region was the strongest market.

Both achieved strong results via premium pricing and higher margins.

Seasonal Trends:

Sales peaked during summer months (July & August), reflecting higher beverage demand.

Pricing vs. Volume:

Retailers like BevCo sold large volumes at low unit prices, which boosted sales quantity but delivered weaker profits.

**Actionable Recommendations**

Optimize Low-Margin Partnerships:

Work with high-volume, low-margin retailers (like BevCo) to slightly increase prices. Even a small change could significantly boost profit without losing customers.

Replicate Success in Growth Markets:

Apply winning strategies from the Northeast region and Sodapop — e.g., premium placement, stronger in-store marketing — in underperforming regions like the Midwest.

Launch Targeted Summer Campaigns:

Leverage the predictable summer demand surge by launching marketing campaigns from May to August.

Focus on high-margin summer beverages such as Powerade and Dasani.

**Deliverables**

Cleaned Dataset: Standardized and structured Excel table (tbl_sales).

PivotTables: Multiple analytical views by retailer, region, brand, and month.

Visuals: Bar, line, scatter, and pie charts to highlight insights.

Interactive Dashboard: Consolidated sheet with slicers for dynamic exploration.

**Conclusion**

This Excel project demonstrates how raw transactional data can be transformed into strategic insights. By identifying high-performing retailers, seasonal opportunities, and margin optimization strategies, Coca-Cola can make data-driven decisions to maximize profitability and strengthen its competitive edge.
