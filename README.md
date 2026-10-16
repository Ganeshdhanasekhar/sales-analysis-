# sales-analysis-
Interactive Power BI dashboard analyzing Superstore sales and profitability, uncovering discount-driven margin loss, regional performance gaps, and top customer/segment trends — backed by SQL analysis on a 4-year, ~10K-record retail transaction dataset.
Project Goal

The goal of this project is to analyze the Superstore's sales and profitability performance to uncover actionable business insights. Specifically, the dashboard aims to answer:

Which product categories and regions drive the most sales and profit?
Are there products or categories that are unprofitable despite high sales?
How does discounting affect profitability?
Who are the most valuable customer segments?
How do shipping modes and order patterns behave over time?
The end goal is a decision-support dashboard that a business/sales manager can use to identify growth opportunities and fix loss-making areas.

Tools Used

power BI-- Dashboard design, DAX measures, interactive visuals Power Query-- Data cleaning and transformation MySQL--Data storage, schema design, and SQL-based analysis Excel / CSV-- Raw data storage and inspection DAX--Calculated measures (Profit Margin, YoY Growth, etc.)

Dataset Resource

File: superstore.csv Rows / Columns: 9,994 rows × 21 columns Time Period: January 2014 – December 2017 Source: Publicly available Superstore sample dataset widely used for BI/analytics practice Grain: One row = one product line item within a customer order

Key Insights: West region has the highest sales, driven by low discounting :** West leads all regions with $725K in sales and $108K in profit, while carrying comparatively lower discount rates than other regions.** Tables and Bookcases are net loss-making sub-categories: despite generating sales, both consistently post negative profit, making them strong candidates for pricing or discount-policy review. Overall sales grew by 56% across the observed period (2014–2017), reflecting strong year-over-year business growth. Top customers by sales are led by Tom Ashbrook ($11.2K), followed by Peter Fuller, Clay Ludtke, and Greg Tran — a small group of high-value repeat customers. 2017 was the strongest year for both sales and profit, continuing an upward trend from 2014.



** dashboard screenshots**

<img width="987" height="555" alt="Screenshot 2026-10-13 at 7 18 04 PM" src="https://github.com/user-attachments/assets/4a8c0e3a-d9f5-4a5e-a1a9-36104a62ec8a" />
<img width="1047" height="584" alt="Screenshot 2026-10-13 at 7 20 24 PM" src="https://github.com/user-attachments/assets/dfc4994f-976c-4aab-8186-d28b76cc9102" />

