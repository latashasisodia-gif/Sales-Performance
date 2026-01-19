# Sales-Performance
This project is an interactive Sales Performance dashboard built in Power BI Desktop to analyze revenue and order trends across products, regions, and discount strategies. The report is designed for business stakeholders to quickly understand how different categories and influencer activities impact overall sales.

Key Features
KPI cards summarizing Total Revenue (~1M), Total Orders (~10K), and Average Discount %, giving an instant overview of business performance.

Bar chart of “Top Product by Revenue” that highlights the highest‑earning categories such as Beverages, Grocery, Snacks, and others, helping identify core revenue drivers.

City selector (Bangalore, Chennai, Delhi, Hyderabad, Mumbai, Pune) that acts as a slicer, enabling users to filter all visuals by region and compare performance across cities.

Clustered bar chart showing “Sum of Total Revenue by Category and Influencer Active” to compare category performance when influencer marketing is active vs not active.

Scatter plot “Discount % vs Orders” to study how different discount levels influence the number of orders for each category and to spot potential sweet spots for pricing or promotions.

Donut chart “Revenue Share by Influencer Activity” that breaks down total revenue contribution between influencer‑active and non‑influencer channels for quick attribution insights.

Business Questions Addressed
What is the overall revenue, order volume, and average discount for the selected period?

Which product categories generate the most revenue and how does this vary across cities?

How does influencer activity affect revenue contribution and category performance?

What relationship exists between discount percentage and order volume across categories?

Tech Stack and Model
Tool: Power BI Desktop.

Data model: Star schema with fact table for sales (orders, revenue, discount, influencer flag) and dimension tables for Products, Categories, and Cities.

Measures: DAX measures for Total Revenue, Total Orders, Average Discount %, and Revenue by Influencer Activity used across visuals.
https://github.com/latashasisodia-gif/Sales-Performance/blob/main/Sales%20Performance.png
