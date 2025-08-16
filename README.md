This project focuses on developing an Inventory Optimization Analysis Dashboard using StockLens, designed to provide businesses with actionable insights into their inventory performance across products, categories, and countries. Inventory management is a critical aspect of supply chain efficiency, and this project aims to identify patterns in stock levels, optimize replenishment strategies, and minimize risks associated with overstocking and stockouts.
By leveraging data visualization, the dashboards provide an end-to-end overview of total stock, stock status, lead time, turnover rate, and distribution by category and geography—helping stakeholders make informed decisions.


OBJECTIVES:
•	To track overall stock levels and monitor product availability across categories.

•	To analyze country-level and warehouse-level stock distribution and highlight underperforming regions.

•	To identify products under reorder point and optimize restocking policies.

•	To evaluate turnover rates and inventory values across product categories and geographies.

•	To provide actionable recommendations that reduce stockouts, improve stock efficiency, and minimize holding costs.

METHODOLOGY:
The methodology adopted for this project included:

•	Data Collection & Cleaning: Extracted raw inventory data (stock levels, unit price, lead time, turnover, reorder points, suppliers, etc.) and standardized it for consistency.

•	Exploratory Data Analysis (EDA): Identified trends, seasonality, and category-wise performance using statistical summaries.

•	Visualization & Dashboarding: Developed interactive dashboards in Power BI (StockLens platform), integrating KPIs, bar charts, maps, and pie charts for intuitive monitoring.

•	Performance Monitoring: Set thresholds for stock sufficiency (In Stock, Low Stock, Out of Stock) and reorder points to flag critical items.

•	Comparative Analysis: Conducted product-wise, category-wise, and country-wise comparisons to evaluate disparities and optimization opportunities.

KEY INSIGHTS:
Dashboard 1: Global Inventory Overview

•	Total Stock: 2.23M units with an inventory value of 1.25B.

•	Average Unit Price: 498.97 with an average lead time of 5,559 days, indicating significant procurement delays.

•	Stock by Month: Peak stock observed in March 2024; fluctuations across months highlight inconsistent supply planning.

•	Product Status: 84.43% of items are in stock, but 15.57% are out of stock—posing risks for demand fulfillment.

•	Category Analysis: Electronics and Toys lead in stockholding; Books and Clothing show higher risks of low stock distribution.

•	Country Distribution: Belgium holds the highest stock, followed by Germany and Italy.

Dashboard 2: Product Category Drill-Down (Books Example)

•	Stock Under Reorder Point: 232 products flagged for restocking.

•	% In Stock: 84.37% with 16% out of stock—aligning with global stock distribution patterns.

•	Supplier Performance: Variation in lead times (7–30 days) across suppliers shows potential bottlenecks in procurement.

•	Product Level Detail: Many products marked as “Out of Stock” despite sufficient reorder points—indicating delays in restocking.

•	Turnover Rate: Maintains a healthy 24.39, but risks exist if stockouts persist.

Dashboard 3: Country-Level & Warehouse Inventory

•	Geographic Spread: 10 countries analyzed; Belgium leads with the highest inventory value (134.22M).

	Germany: Faces the highest number of products below reorder point (33), signaling critical supply issues.

	Netherlands: Exhibits the highest turnover rate (25.09), suggesting efficient stock circulation.

•	Warehouse Distribution: Peaks observed in AISLE-02-SHELF-03 with 8K units; inventory clustering may lead to imbalances across storage locations.

•	Category Stock: Home & Garden (381K) leads in total stock, followed by Books (374K) and Office Supplies (368K).

RECOMMENDATIONS:

•	Address Stockouts: With 15.57% of products out of stock, businesses should prioritize replenishment for high-demand categories (Books, Clothing).

•	Supplier Management: Lead times need to be optimized by diversifying suppliers and negotiating faster delivery terms.

•	Country-Level Balancing: Germany’s low stock and reorder issues should be addressed with proactive redistribution from Belgium (overstocked).

•	Warehouse Optimization: Avoid clustering by redistributing stock more evenly across aisles to reduce congestion and improve accessibility.

•	Forecasting & Demand Planning: Implement predictive analytics to anticipate seasonal peaks (e.g., March 2024) and align procurement schedules accordingly.

•	Reorder Policy Adjustment: Products flagged below reorder points should trigger automated purchase orders to prevent disruptions.

•	Continuous Monitoring: Leverage dashboards in real-time for ongoing performance tracking, ensuring stock sufficiency aligns with turnover expectations.
