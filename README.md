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

## 📊 Key Insights

### 1. Furniture drives volume but barely turns a profit
Furniture generated **$451.5K** in sales but only a **2.2% profit margin** (~$10K profit) — far below Technology (19.2%) and Office Supplies (11.6%). The **Tables sub-category is actively losing money** (‑$11,092 on $119K in sales), making it the single biggest drag on furniture profitability.

| Category | Sales | Profit | Margin |
|---|---|---|---|
| Technology | $470.6K | $90.5K | 19.22% |
| Office Supplies | $643.7K | $74.8K | 11.62% |
| Furniture | $451.5K | $10.0K | 2.22% |

### 2. ~19% of orders are sold at a loss
**1,098 of 5,901 orders (18.6%)** have negative profit, totaling **‑$91,710 in losses**. Binders, Tables, and Machines are the top three loss-generating sub-categories — worth investigating for pricing/discounting strategy.

| Sub-Category | Total Loss |
|---|---|
| Binders | ‑$22.7K |
| Tables | ‑$19.2K |
| Machines | ‑$19.0K |
| Chairs | ‑$5.9K |
| Bookcases | ‑$5.1K |

### 3. Copiers and Accessories are the best-margin performers
Despite modest sales volume, **Copiers convert 72% of sales into profit** ($59.7K sales → $42.8K profit), and Accessories turn $122.3K in sales into $25.3K profit. These are the strongest candidates for upsell and marketing focus.

| Sub-Category | Sales | Profit | Margin |
|---|---|---|---|
| Copiers | $59.7K | $42.8K | 71.6% |
| Accessories | $122.3K | $25.3K | 20.7% |
| Phones | $196.6K | $22.3K | 11.3% |

### 4. Regional profitability doesn't track sales volume
The **West** leads on both sales ($522K) and margin (13.0%), but the **Central region lags at just 8.05% margin** despite solid sales ($341K) — the lowest profitability of any region, suggesting heavier discounting or higher costs there.

| Region | Sales | Profit | Margin |
|---|---|---|---|
| West | $522.4K | $67.9K | 12.99% |
| East | $450.2K | $53.4K | 11.86% |
| South | $252.1K | $26.6K | 10.53% |
| Central | $341.0K | $27.5K | 8.05% |

---

**Bonus — Payment behavior:** Cash on Delivery (COD) is the most common payment method at 42% of orders, followed by Online (37%) and Cards (22%).

## 📂 How to View

1. Download `dashboard/PBI_Hackathon_SuperstoreSales.pbix`
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Explore interactively using the slicers and filters on each report page

## 📬 Connect

[LinkedIn](https://www.linkedin.com/in/pijush-paul-4a6764197)
