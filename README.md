# Amazon Sales Analytics Dashboard (Power BI)

An interactive Power BI dashboard built to track and analyze Amazon sales performance, profit margins, order volumes, and customer behavior across global markets. 

I built this project to take raw transactional sales data and turn it into a clean, self-service reporting tool that helps stakeholders spot revenue drivers, identify underperforming sub-categories, and track year-over-year growth.

---

## Dashboard Preview

![Dashboard Overview](Dashboard%20Preview/1.png)

![Detailed Analytics View](Dashboard%20Preview/2.png)

---

## Key Metrics & KPIs Tracked

### Core Headline KPIs
* **Total Sales:** $12.64M
* **Total Profit:** $1.47M
* **Overall Profit Margin:** 11.63% *(calculated across total revenue)*
* **Total Quantity Sold:** 178K units
* **Average Revenue per Unit:** ~$71.01
* **Average Profit per Unit:** ~$8.26

### Analytical Breakdowns
* **Sub-Category Performance:** Sales volume, net profit, and margin comparison across all product sub-categories.
* **Customer Segment Share:** Revenue and order volume distribution across Consumer, Corporate, and Home Office segments.
* **Regional & Market Trends:** Geographic performance across global markets tracked year-over-year.

---

## Business Questions Answered

Before designing the layout, I structured the data model and visuals around five core questions:
1. How are overall revenue, profit, and unit sales trending?
2. Which product sub-categories are driving the highest top-line sales?
3. Are high-selling sub-categories actually profitable, or are certain items eating into margins?
4. How does purchasing behavior differ across customer segments (Consumer, Corporate, Home Office)?
5. Which regional markets are outperforming others, and how does that shift year over year?

---

## Features & Functionality

* **Executive KPI Cards:** Instant visibility into total revenue, net profit, and total units moved.
* **Sub-Category Breakdown:** Side-by-side comparison of sales vs. profit by product sub-category to spot high-volume, low-margin bottlenecks.
* **Dynamic Slicers:** Interactive filtering by **Year**, **Customer Segment**, and **Market** so users can drill down into specific regions or timeframes without altering the underlying report.

---

## Tech Stack

* **Power BI Desktop:** Data modeling, report layout, and interactive visuals.
* **Power Query:** Data cleaning, transformation, and standardization.
* **DAX (Data Analysis Expressions):** Custom measures for aggregating sales, profit, and quantity metrics.

---

## Repository Structure

```text
├── Dashboard/
│   └── Amazon_Sales_Dashboard.pbix    # Main Power BI project file
├── Dashboard Preview/
│   ├── 1.png                          # Dashboard overview screenshot
│   └── 2.png                          # Detailed analytics screenshot
└── README.md                          # Project documentation
