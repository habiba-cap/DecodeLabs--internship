# DecodeLabs--internship
Project: Retail Sales 
Internship: DecodeLabs – Data Science
Developer: Habiba Mohamed 

# Project Objective
--- The objective of this project was to transform raw retail transaction data into a high-impact visual dashboard. By cleaning messy datasets and applying advanced visualization techniques, I provided the business with a clear view of revenue drivers, consumer behavior, and operational demand.

# Technical Implementation
---Data Preprocessing & CleaningImputation Strategy: Handled missing Price Per Unit values using category-based medians to preserve the natural pricing structure of the inventory.
---Math Validation: Programmatically recalculated Total Spent (Price x Quantity) to ensure 100% accuracy across all 12,000+ records.
---Outlier Control: Applied a 99th percentile cap to revenue figures to ensure the final dashboard reflects standard business operations rather than statistical noise.Date ----Standardization: Converted transaction logs into standard datetime objects for accurate time-series analysis.

CompletedData Cleaning: Handled missing values using category-based median imputation and recalculated totals for mathematical consistency.
Outlier Management: Identified and capped high-value outliers (99th percentile) to ensure statistical models weren't skewed.
Exploratory Data Analysis (EDA): Analyzed revenue distribution, payment preferences, and inventory demand.
Visual Storytelling: Developed a comprehensive 8-plot dashboard using Matplotlib and Seaborn to visualize the business "heartbeat."
Predictive Analytics: Established a strong correlation ($R^2 \approx 0.90$) between quantity and total spend for future revenue forecasting.
Repository Structure retail_store_sales.csv: The raw dataset provided by DecodeLabs.
analysis_script.py: The shorthand Python script for cleaning and visualization.
retail_sales_report.png: The final exported dashboard.
How to Run
Ensure you have pandas, seaborn, and matplotlib installed.
Place the retail_store_sales.csv in the same directory as the script.
Run the script to see the data summary and generate the dashboard.
Main InsightsTop Performer: The "Butchers" category is the primary revenue driver.
Channel Shift: Online sales now account for a significant portion of the total market share, heavily utilizing Digital Wallets.
Volume over Price: Quantity sold has a much higher correlation with revenue than unit price changes.
