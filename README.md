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



# Data Analytics Task 2 — Advanced Excel Analysis & Business Reporting

## Objective
Build on the Week 1 cleaned dataset to perform advanced analysis, segment customers, calculate growth/variance, and produce a business-focused report using Excel.

## Workflow
- **Raw_Data / Cleaned_Data** — unchanged from Week 1, with Segment, Month, MonthSort, and Quarter added as columns
- **Advanced_Analysis** — SUMIFS, COUNTIFS, AVERAGEIFS, IFS, VLOOKUP/INDEX-MATCH, text and date functions, category contribution %, month-over-month growth %, customer segmentation (High/Medium/Low value), top/bottom performers
- **Pivot_Analysis / Pivot_CatRegion / Pivot_Segment / Pivot_Month / Pivot_Quarter** — 4 native Pivot Tables with Pivot Charts: Category × Region, Customer Segment, Monthly, and Quarterly sales
- **Business_Report** — KPI table and data-backed insights and recommendations

## Key Findings
- Total sales: €1,552,071 across 11,971 transactions
- Sales dipped 3.7% from 2022 to 2023, then grew 6.8% from 2023 to 2024
- Top category: Butchers (€208,118) | Top region: Central (€314,780)
- High Value customers (top third by spend) drive 37.8% of total revenue
- 33.6% of orders used a discount

## Recommendations
1. Protect and grow the High Value customer segment
2. Investigate the cause of the 2023 sales dip
3. Prioritize spend by margin/segment value over category or region, since both are tightly clustered
4. Reassess discount strategy against actual incremental impact

## Tools
Microsoft Excel — Pivot Tables, Pivot Charts, Conditional Formatting, advanced formula-based analysis

## Note
GitHub's in-browser preview may not render Pivot Tables/charts correctly — please download the file and open in Excel to view the full workbook (Pivot_CatRegion, Pivot_Segment, Pivot_Month, Pivot_Quarter tabs and all charts).



# Data Analytics Task 3 — Data Visualization & Business Intelligence Dashboard

## Objective
Turn the analyzed retail sales dataset into a one-page, interactive Business Intelligence dashboard that helps decision-makers quickly understand performance, trends, and where to act.

## Workflow
- **Data** — cleaned dataset with Segment, Month, and Quarter columns
- **KPI_Summary** — Total Sales, Total Orders, Total Customers, Average Order Value, Sales Growth %, Top Category/Region
- **Visualizations** — supporting bar, pie, and line charts for Category, Region, Monthly, Quarterly, and Segment performance
- **Dashboard** — one-page view: 6 KPI cards, 3 live PivotCharts (Category × Region, Segment, Monthly Trend), Top/Bottom Performers summary
- **Insights** — trends, best/worst performers, customer patterns, and 5 recommendations

## Interactivity
- **Slicers** (Region, Segment) and a **Timeline** (Transaction Date) are connected to all 3 PivotCharts on the Dashboard — clicking a slicer button filters every chart together, live.

## Key Findings
- Total sales: €1,552,071 across 11,971 transactions
- Sales dipped 3.7% from 2022 to 2023, then grew 6.8% from 2023 to 2024
- Top category: Butchers (€208,118) | Top region: Central (€314,780)
- High Value customers (top third by spend) drive 37.8% of total revenue
- Category and regional performance are both tightly clustered — no single area dominates

## Recommendations
1. Prioritize retention for the High Value customer segment
2. Investigate the cause of the 2023 sales dip before scaling 2024 tactics further
3. Focus investment on margin and customer segment value rather than chasing one "top" category or region
4. Use the dashboard's monthly trend view to catch early signs of another dip
5. Test whether discounting is driving real incremental volume, or just eroding margin

## Tools
Microsoft Excel — Pivot Tables, PivotCharts, Slicers, Timeline, Conditional Formatting, KPI dashboard design

## Note
GitHub's in-browser preview may not render Pivot Tables, PivotCharts, slicers, or the timeline correctly — please download the file and open in Excel to use the full interactive dashboard.
