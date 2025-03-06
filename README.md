E-commerce Data Analysis Project
Overview
This project analyzes an e-commerce dataset to uncover insights about sales performance, seller operations, product categories, customer behavior, and geographical trends. By applying data cleaning, exploratory data analysis, and visualization techniques, the project highlights key metrics such as total revenue, order counts, cancellation rates, payment methods, and delivery performance.
Key Analyses & Findings
Data Cleaning

Missing Values: Handled null entries in critical columns (e.g., price, product_weight_g) via dropping or imputation.
Duplicates: Removed duplicate rows based on order_id or product_id.
Type Conversions: Converted date/time columns to datetime and numerical columns to appropriate types.
Descriptive Statistics

Total Revenue: Summation of price + freight_value for delivered orders.
Average Order Value: Identified spending patterns by city, product category, and seller.
Review Scores: Tracked customer satisfaction levels by seller and product.
Seller Performance

Freight Costs: Analyzed which sellers incur higher shipping expenses.
Gross Margin: Estimated margins (if cost data available).
Review Score Distribution: Sellers with high volume but low scores flagged for potential quality issues.
Product-Level Analysis

Top Categories: Categories contributing the most revenue.
Cancellation & Return Rates: Identified products with higher return/cancellation ratios, possibly indicating quality or listing issues.
Geographical Insights

City & State Analysis: Found regional hotspots with high revenue and order counts.
Shipping Times: Correlated with distance or logistics partners in certain regions.
Time Analysis

Seasonal Trends: Identified sales spikes during specific months or holidays.
Day-of-Week Patterns: Detected potential weekend vs. weekday differences.
Forecasting

Monthly Revenue Forecast: Created basic predictive models (e.g., ARIMA, Prophet) to anticipate future demand.
Scenario Planning: Explored how promotional events or new product launches might shift revenue trajectories.
