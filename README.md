# Profit & Sales Performance Dashboard (Excel)

An interactive Excel dashboard that analyses 500 retail orders across five Nigerian branches to show where revenue and profit come from, and how much of the sales pipeline is actually converting.

## The Business Problem

The business had order-level data but no clear view of which branches, categories and months drive revenue and profit, or how many orders are completed. This dashboard answers those questions in one place.

## Dataset

- **Records:** 500 invoices (Jan to Dec 2025)
- **Columns (15):** Invoice_ID, Date, Customer_Name, Branch, Salesperson, Product, Category, Quantity, Unit_Price, Total_Sales, Discount, Profit, Payment_Method, Order_Status, Month
- **Branches:** Lagos, Ibadan, Port Harcourt, Kano, Abuja
- **Categories:** Electronics, Fashion, Accessories, Beauty, Clothing

## Data Checks

- No missing values and no duplicate invoice IDs
- `Total_Sales` equals `Quantity x Unit_Price` on every row
- `Month` matches the invoice `Date` on every row

## Dashboard Features

- 4 KPI cards: Total Revenue, Total Profit, Total Quantity, Total Orders
- 4 charts: Revenue by Category, Orders by Status, Revenue by Branch, Monthly Revenue
- 4 slicers (Branch, Order Status, Month, Category) connected to every pivot table and chart
- Key Insights panel on the dashboard

## Key Metrics

| Metric | Value |
|---|---|
| Total Revenue | ₦251,592 |
| Total Profit | ₦95,462 |
| Profit Margin | 37.9% |
| Total Quantity | 1,560 |
| Total Orders | 500 |

## Key Insights

- **Lagos leads** branch revenue at ₦57,143 (23% of total); Abuja is lowest at ₦43,893.
- **Electronics and Fashion** generate 58% of revenue and profit (₦146,772).
- **Clothing** is the weakest category at ₦28,326 (11% of revenue).
- **53% of orders** (265 of 500) are Pending or Cancelled. Cancelled orders alone make up ₦65,602 (26%) of reported revenue, while Delivered and Shipped total ₦118,247.
- **Revenue peaked in November** (₦28,666) and was lowest in January (₦16,565).
- **Profit margin is about 38%** across every category and branch, so profit follows sales volume.

## Recommendations

1. Reduce pending and cancelled orders by reviewing payment confirmation, stock availability and delivery follow-up.
2. Report realised (Delivered and Shipped) revenue alongside total revenue.
3. Learn from Lagos and test its approach in Abuja.
4. Keep Electronics and Fashion well stocked, and review pricing or promotion for Clothing.
5. Plan stock and marketing around the November peak and low months such as January and July.
6. Test pricing and discount levels (average discount is 10%) to lift margin.

## Tools Used

- Microsoft Excel: pivot tables, slicers, charts, dashboard design

## Files

- `Profit_and_sales_analysis.xlsx`: dataset, pivot tables and dashboard
- `Profit_and_Sales_Analysis_Report.pdf`: 2-page summary report

## Author

**Zainab Danjuma**
