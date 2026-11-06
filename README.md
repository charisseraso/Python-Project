
## Project Overview
This project analyzes sales transactions and customer information to understand business performance, product/category contribution, and customer spending patterns. Python and pandas are utilized in this analysis and matplotlib/streamlit are used for dashboard creation

## Project Files

### Cleaned datasets
- `Cleaned_customers.csv` — cleaned customer records.
- `Cleaned_products.csv` — cleaned product records.
- `Cleaned_orders.csv` — cleaned order records.
- `Cleaned_order_items.csv` — cleaned order-item records.
- `Sales_fact_table.csv` — consolidated dataset used for sales analysis.

### Exported charts
- `01_monthly_revenue.png` — monthly revenue trend.
- `02_revenue_by_category.png` — revenue by product category.
- `03_top_10_products.png` — top 10 products by revenue.
- `04_revenue_by_region.png` — revenue by region.
- `05_customer_spend_distribution.png` — distribution of customer spending.
- `06_order_status_breakdown.png` — order status breakdown.

## Tools and Libraries
- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Streamlit 


## Insights

Executive Summary
Completed transactions generated ₱4,811,841.80 in product-line revenue across 9,811 completed orders and 4,307 customers.
 Average order value (AOV) was ₱421.50 Media order value was at ₱421.50


KEY FINDINGS
• Monthly Revenue: Monthly revenue fluctuated between approximately ₱230,000 and ₱280,000,
  showing relatively consistent sales performance throughout the period.
• Category: Electronics generated the highest revenue at approximately ₱890,000, followed by Toys at approximately ₱850,000. 
  Groceries recorded the lowest revenue at approximately ₱700,000.
• Region: Central Luzon led at ₱839,400.49; CALABARZON had the lowest regional total (₱760,186.98).
• Product: UrbanWear Sports 328 ranked first with approximately 200 units sold, followed by NovaTech Toys 605 with 
  approximately 185 units and NovaTech Sports 827 with approximately 180 units.
• Customer spending: Most customers spent below ₱2,500, while only a small number reached spending levels above ₱5,000.
• Order Cancellations: Monthly cancellations ranged from approximately 40 to 60 orders, peaking in October 2024 and February 2025.

RECOMMENDATIONS
• Maintain stock and visibility for leading products, while checking profitability before expanding promotions.
• Study leading categories and regions to identify what and where demands are coming from
• Track AOV and customer-spend segments over time; test cross-selling to increase order value.
• Review cancellation and return reasons by month, product, and region to identify preventable issues.
