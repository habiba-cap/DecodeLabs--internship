# DecodeLabs--internship
Project: Retail Sales

Internship: DecodeLabs – Data Science

Developer: Habiba Mohamed 

# Project Objective
- The objective of this project was to transform raw retail transaction data into a high-impact visual dashboard. By cleaning messy datasets and applying advanced visualization techniques, I provided the business with a clear view of revenue drivers, consumer behavior, and operational demand.

# Technical Implementation
-Data Preprocessing & CleaningImputation Strategy: Handled missing Price Per Unit values using category-based medians to preserve the natural pricing structure of the inventory.


-Math Validation: Programmatically recalculated Total Spent (Price x Quantity) to ensure 100% accuracy across all 12,000+ records.


-Outlier Control: Applied a 99th percentile cap to revenue figures to ensure the final dashboard reflects standard business operations rather than statistical noise.Date ----Standardization: Converted transaction logs into standard datetime objects for accurate time-series analysis.

# 2. The Executive Dashboard (EDA)
I designed an 8-panel dashboard to tell a complete story of the retail environment:

Revenue Leaders: A horizontal breakdown of which product categories drive the most income.

Monthly Sales Pulse: A dedicated time-series trend (highlighted in red) to track monthly business momentum.

Channel Share: A donut chart comparing the success of Online vs. In-Store sales.

Statistical Heatmap: Analyzed the correlation between price points and quantity sold.

Payment Logistics: Identified how customers prefer to pay at different store locations.

Inventory Demand: Visualized total units sold per category to assist with stock planning.

# Key Business Takeaways
High-Value Categories: The "Butchers" and "Electric Household" segments are the primary revenue anchors for the store.

Digital Trends: Online shopping shows significant strength, particularly when paired with Digital Wallet payment methods.

Growth Trajectory: The Monthly Sales Trend shows consistent upward movement, indicating a healthy and growing customer base.
 Price: Quantity sold has a much higher correlation with revenue than unit price changes.
