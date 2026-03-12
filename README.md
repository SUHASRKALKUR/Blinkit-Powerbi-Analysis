# Blinkit Sales & Operations Dashboard

This project analyzes Blinkit's sales performance, product demand, and delivery operations using Power BI.

## Tools Used
- Microsoft Excel (Data Cleaning)
- Power BI (Data Transformation & Visualization)

## Dataset
The dataset contains information about:
- Product Name
- Category
- Brand
- Price & Discount
- Ratings & Reviews
- City & Seller
- Stock & Sold Quantity
- Delivery Status

## Data Cleaning (Excel)
Before building the dashboard, the dataset was cleaned using Excel.

Steps performed:
- Removed duplicate values
- Standardized column names
- Cleaned product names using Flash Fill
- Validated final price after discount
- Checked for null values
- Verified start and expiry dates

## Data Transformation (Power BI)
Using Power Query, additional calculated columns were created.

Revenue = Final Price × Sold Quantity  
Profit = Revenue × Profit Margin %

## DAX Measures

### Page 1 KPIs
- Total Revenue
- Total Profit
- Total Units Sold
- Average Rating

### Page 2 KPIs
- Total Stock
- Total Units Sold
- Average Delivery Time

## Dashboard Screenshots

### Page 1 – Sales Overview
![Dashboard Page 1](images/dashboard_page1.png)

### Page 2 – Operational Insights
![Dashboard Page 2](images/dashboard_page2.png)

## Key Insights
- Household category generates the highest revenue.
- Customer ratings remain consistently high.
- Some cities contribute higher profits.
- Most deliveries are completed on time.

## Project Outcome
The dashboard provides insights into:
- Sales performance
- Customer satisfaction
- Delivery efficiency
- City-wise profitability

These insights can support better business decisions.
