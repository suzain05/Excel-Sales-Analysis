# Excel Portfolio — Retail Sales Performance Dashboard
An Excel dashboard analyzing 3 months (April–June 2026) of retail sales data for a retail apparel business
built entirely with pivot tables, slicers, and charts. Covers revenue trends, city and category performance, payment methods, delivery status, and sell-through rate.

📂 File: [DATA ANALYTICS EXCEL PORTFOLIO.xlsx](DATA%20ANALYTICS%20EXCEL%20PORTFOLIO.xlsx)

# Objective
Identify which product categories and cities drive the most revenue, understand customer buying patterns, and evaluate inventory sell-through helping the business prioritize stock and marketing spend where it matters most.

# Dataset
140 orders across 10 cities and 23 product categories, covering order details, customer demographics, category, city, delivery status, payment method, price, quantity, revenue, and customer rating.

 **Due to company data privacy policy, only a limited 3-month window with a fixed set of price tiers was shared for this analysis, rather than the full product catalog and pricing history.**

## Raw Dataset

This is the raw sales dataset used for the analysis.

![Raw Dataset](screenshots/RAW%20DATASET%20IMAGE%201.png)

# processed data

**The dataset after cleaning and processing**

![Processed Dataset](https://raw.githubusercontent.com/suzain05/Excel-Sales-Analysis/main/screenshots/PROCESSED_DATA%20IMAGE%201.png)
![Processed Dataset](https://raw.githubusercontent.com/suzain05/Excel-Sales-Analysis/main/screenshots/PROCESSED_DATA%20IMAGE%202.png)

*Cleaned data ready for analysis : removed duplicates/blanks, standardized formats, and structured for pivot tables.*

# TOOLS AND TECHNOLOGIES 
# Microsoft Excel 
Pivot Tables, Slicers, Power Query, Charts (donut, bar, combo)

 | Sheet | What it covers |
|---|---|
| Monthly Orders & Revenue | Orders and revenue trend across April–June |
| Revenue by City | City-wise revenue breakdown |
| Gender Wise Sales | Revenue split by customer gender |
| Category Wise Revenue | Revenue ranked by product category |
| Payment Method Analysis | Revenue share by payment method (Cash / UPI / Net Banking) |
| Delivery Status Analysis | Order breakdown by delivery stage |
| Sell-Through Rate Analysis | Units sold vs. stock received, by category |
| Dashboard | All of the above combined into one interactive view |


# Sample Views
 
## 📊 Main Dashboard
The dashboard provides an interactive overview of retail sales performance across revenue, product categories, cities, payment methods, delivery status
and sell-through rate.

![Main Dashboard](screenshots/DASHBOARD.png)


## 📝 Business Questions Solved

- Total Revenue Analysis
- Revenue by Category
- Revenue by City
- Monthly Sales Analysis
- Top 5 Categories by Revenue
- Payment Method Analysis
- Customer Rating Analysis
- Delivery Status Analysis
- Units Sold Analysis
- Sell-Through Rate Analysis
- Interactive Dashboard with Slicers
- KPI Summary and Sales Insight

## 📈 Key Insights

- **Saree** emerged as the top-performing category, driving the highest share of revenue
- **Chennai** led all cities in revenue, followed by Bangalore and Mumbai
- Generated **₹6,61,472** in total revenue across **140 orders** (avg order value ₹4,725)
- **UPI** was the dominant payment method among customers
- **Floral-Dress, Cotton-Kurti, and Denim-Jacket** recorded the highest sell-through rate (60%), while **FormalShirt** had the lowest (21.73%)  suggesting stronger customer demand for ethnic and casual wear over formal wear

  ## Related Project
  
This same dataset is also analyzed in a SQL portfolio project using MySQL covering the same 3-month window with 30 queries from basic filtering to window functions and CTEs.

**Fathima Suzain · Data Analytics Portfolio · 2026**
