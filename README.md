# Superstore Sales Dashboard (Power BI)

An interactive Power BI dashboard analyzing sales, profit, and returns performance for a retail superstore across regions, categories, and customer segments.

## 📊 Project Overview

This project explores order-level retail transaction data to answer key business questions:
- Which regions and product categories drive the most revenue and profit?
- How do returns impact overall profitability?
- Which customer segments and ship modes are most valuable?
- How do sales trends move over time?

## 🗂️ Dataset

`data/SuperStore_Sales_Dataset.csv` — ~5,900 order-line records with the following fields:

| Field | Description |
|---|---|
| Order ID, Order Date, Ship Date, Ship Mode | Order and fulfillment details |
| Customer ID, Customer Name, Segment | Customer information |
| Country, City, State, Region | Geographic breakdown |
| Product ID, Category, Sub-Category, Product Name | Product hierarchy |
| Sales, Quantity, Profit, Returns | Core performance metrics |
| Payment Mode | Payment method used |

## 🛠️ Tools Used

- **Power BI Desktop** — data modeling, DAX measures, interactive report pages
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures (e.g., Total Sales, Profit Margin, Return Rate)

## 📈 Dashboard Highlights

- KPI cards for Total Sales, Total Profit, and Return Rate
- Regional and category-level sales breakdown
- Time-series trend analysis of sales and profit
- Segment and ship-mode performance comparison
- Interactive slicers for filtering by date, region, and category

📄 [View full dashboard export (PDF)](exports/dashboard_overview.pdf)

## 🔑 Key Insights

*(Fill in 3-5 bullet points once you've reviewed your findings, e.g.:)*
- [Region] generates the highest sales but [Region] has the strongest profit margin
- [Category] has the highest return rate, impacting overall profitability
- Sales peak during [time period], suggesting seasonal demand

## 📂 How to View

1. Download `dashboard/PBI_Hackathon_SuperstoreSales.pbix`
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Explore interactively using the slicers and filters on each report page

## 📬 Connect

[LinkedIn](https://www.linkedin.com/in/pijush-paul-4a6764197)
