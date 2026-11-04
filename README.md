# Sales Tracking Dashboard 2026

An Excel sales analysis project that uses PivotTables and charts to explore revenue, profit, product categories, sales regions, and quantities sold.

## Project overview

This project demonstrates how Excel can turn transaction-level sales data into a dashboard that supports business performance monitoring and decision-making. The workbook contains a primary data sheet, a dashboard sheet, and supporting analysis sheets.

> **Data note:** The workbook is named "Sales Tracking Dashboard 2026", but the dates in the primary dataset run from **2 January 2015 to 8 July 2015**. The analysis below reflects the dates actually contained in the workbook, not the filename.

## Business questions

- Which product category contributes the most revenue and profit?
- How does sales revenue change over the available months?
- Which region generates the most revenue and profit?
- Which product sub-categories have the highest quantities sold?
- Where are the main opportunities and risks in sales performance?

## Dataset

The primary `DATA` worksheet contains **1,952 records** and 8 columns:

| Field | Description |
|---|---|
| Category | Broad product category |
| Revenue | Revenue recorded for the transaction |
| Ship Date | Transaction shipping date used for time analysis |
| Region | Sales region |
| product sold | Product-related value recorded in the source data |
| Profit | Profit recorded for the transaction |
| Product Sub-Category | More detailed product classification |
| Quantity | Units sold |

The primary data sheet has no blank values in these eight fields. The workbook also includes a supplementary `Sheet10` worksheet; the dashboard analysis and headline figures in this README are based on the 1,952 records in `DATA`.

## Tools and Excel techniques

- Microsoft Excel
- PivotTables for aggregating sales and profit
- PivotCharts/charts for visual comparisons and trends
- Date grouping for monthly analysis
- Category, region, and product sub-category analysis
- Dashboard presentation

The workbook's analysis is based on PivotTables and charts. No ordinary worksheet formula cells were detected in the inspected sheets, so this documentation does not attribute specific formulas to the project.

## Dashboard and analysis areas

The workbook includes the following dashboard support sheets:

- **CATEGORY** – revenue by product category.
- **SALES BY YEAR** – time-based sales summary; the available primary data covers January to July 2015.
- **PROFIT BY YEAR** – time-based profit summary.
- **QUANTITY SOLD BY SUB CATEGORY** – quantity analysis by product sub-category.
- **SALES BY REGION** – revenue comparison across regions.
- **PROFIT BY REGION** – profit comparison across regions.
- **DASHBOARD** – main dashboard canvas.

## Key findings from the primary dataset

| Metric | Result |
|---|---:|
| Sales records | 1,952 |
| Total revenue | 45,908,549.67 |
| Total profit | 224,077.61 |
| Total quantity sold | 25,268 |
| Overall profit margin | 0.49% |

*The workbook does not specify a currency, so the revenue and profit figures are shown without a currency symbol.*


## Dashboard Review
<img width="414" height="488" alt="Screenshot 2026-11-04 180815" src="https://github.com/user-attachments/assets/b48fcf8a-72a3-4d63-9188-331b5c1aac2c" />

### Category performance

- **Office Supplies** generated the highest revenue: 17,817,788.83, approximately 38.81% of total revenue.
- Office Supplies also recorded the highest total profit: 89,525.01.
- Furniture generated 15,551,635.99 in revenue.
- Technology generated 12,539,124.85 in revenue.

### Regional performance

- **East** recorded the highest revenue at 15,926,832.64.
- **Central** recorded the highest profit at 77,365.47.
- **South** recorded a negative total profit of -14,424.05 despite generating 6,053,349.81 in revenue.
- West generated 14,865,665.09 in revenue and 75,844.79 in profit.

### Monthly performance

- **May 2015** was the strongest month in the available data, with revenue of 12,712,234.58.
- July recorded 481,194.85, but the dataset ends on **8 July 2015**. It is therefore a partial month and should not be compared directly with the complete months.
- January and March recorded negative aggregate profit in the primary dataset, making them useful periods for further investigation.

### Product sub-category performance

- **Paper** had the highest total quantity sold, with 3,481 units.
- Pens & Art Supplies followed with 2,744 units.
- Binders and Binder Accessories recorded 2,554 units.

## Business recommendations

1. **Investigate the South region:** Review discounting, operating costs, product mix, and pricing because the region recorded an overall loss.
2. **Protect profitable category performance:** Maintain availability and monitor margins for Office Supplies, while exploring opportunities to improve Technology and Furniture performance.
3. **Review low-profit periods:** Investigate the transactions behind January and March losses to identify products, customers, or pricing decisions affecting profitability.
4. **Use complete periods for comparisons:** Exclude or clearly label July as a partial month when comparing monthly performance.
5. **Monitor both revenue and profit:** High revenue does not automatically mean strong profitability, as the South region illustrates.

## How to explore the workbook

1. Open the Excel workbook.
2. Review the `DATA` sheet to understand the source records.
3. Open the `DASHBOARD` sheet to explore the visual summary.
4. Use the supporting analysis sheets to examine category, time, region, and sub-category performance.
5. Refresh the PivotTables if the source data is changed or extended.

## Project skills demonstrated

- Data inspection and validation
- Sales and profit analysis
- PivotTable reporting
- Chart-based data visualisation
- Business insight generation
- Translating analysis into recommendations

## Repository

This project is part of my Excel data analytics portfolio.

**Author:** Goodness Feranmi  
**GitHub:** [Godspeedxreal](https://github.com/Godspeedxreal)  
**LinkedIn:** [Connect with me](https://www.linkedin.com/in/ogunkunle-goodness-b47186412)  
**Location:** Ibadan, Oyo State, Nigeria
