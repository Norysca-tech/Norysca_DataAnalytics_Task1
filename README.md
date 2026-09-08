# Data Analytics Task 1 — Excel Data Cleaning & Analysis

## Objective
Clean a raw retail sales/customer dataset and turn it into an analysis-ready workbook, then extract business insights using Excel formulas, Pivot Tables, and charts.

## Dataset
12,575-row retail transaction dataset — Transaction ID, Customer ID, Category, Item, Price, Quantity, Total Spent, Payment Method, Location, Transaction Date, Discount Applied. Source data had no geographic Region field, so I added one via a Customer ID → Region lookup table and VLOOKUP.

## Workflow
- **Raw_Data** — original dataset, unmodified
- **Cleaned_Data** — missing values reconstructed (Price/Quantity/Total cross-derived where possible), 604 unrecoverable rows removed, duplicates checked (0 found), text and dates standardized, Region added
- **Analysis** — SUM, AVERAGE, COUNT, COUNTIF, SUMIF, SUMIFS, IF, VLOOKUP, text and date functions
- **Pivot_Analysis / Pivot_Category / Pivot_Region / Pivot_Monthly** — Pivot Tables and Pivot Charts for sales by category, region, and month
- **Insights** — key findings and recommendations

## Key Findings
- Total sales: €1,552,071 across 11,971 cleaned transactions
- Top category: Butchers (€208,118) | Top region: Central (€314,780)
- January sales spike (€174,421) stands out well above other months

## Tools
Microsoft Excel — Tables, Conditional Formatting, Pivot Tables, Pivot Charts, formula-based analysis
