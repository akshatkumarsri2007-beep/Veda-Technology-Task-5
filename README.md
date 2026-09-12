# Veda-Technology-Task-5: Excel Data Analysis & Insights

## Objective
Analyze a structured retail sales dataset in Microsoft Excel using formulas (`SUMIFS`, `COUNTIFS`, `AVERAGEIFS`), sorting, filtering, PivotTables, and key performance indicators (KPIs) to answer business questions and present executive findings.

## Dataset
- **Source:** Retail Sales Performance Dataset
- **Rows:** 1,200
- **Columns:** 17

## Tools Used
- Microsoft Excel
- Python (Pandas, ReportLab)
- Power BI / PDF Reporting

## Key Business Insights & Analytical Findings

| Dimension | Issue / Business Question | Analytical Insight & Resolution |
|---|---|---|
| `Category` | Which product categories drive the highest revenue vs. transaction volume? | **Furniture** dominated overall sales ($7.81M, 57.7% share), while **Grocery** led in order frequency (256 orders) despite low overall revenue ($0.51M). |
| `Region` | Which regions lead in revenue and where should expansion focus? | The **South ($3.91M)** and **East ($3.74M)** regions led revenue generation; the **West ($2.62M)** lagged behind and was identified as a key expansion target. |
| `Seasonality` | How does revenue fluctuate across months? | Revenue peaked sharply during **August ($1.77M)** and **December ($1.48M)**, signaling the need for Q3/Q4 stock buildup. |
| `Payment Mode` | What are customer payment preferences? | **Cash on Delivery** led at 22.5% of orders, but digital channels (**UPI, Cards, Net Banking**) collectively processed ~60% of transactions. |
| `Segment` | Which customer segments are most profitable? | **Small Business (33.3% margin)** and **Corporate (33.0% margin)** yielded higher profit margins than individual retail Consumers (31.8%). |

## Process
1. **Workbook Architecture:** Structured the workbook into 4 dedicated tabs (`Raw Data`, `Formulas`, `PivotTables`, `Summary`) to keep the raw data untouched.
2. **Formula Implementation:** Applied `SUMIFS`, `COUNTIFS`, `AVERAGEIFS`, and `COUNTA` to calculate high-level business KPIs and filtered summaries.
3. **PivotTable Analysis:** Built live PivotTables to slice sales and profit by Product Category, Region, Month, Payment Mode, and Customer Segment.
4. **Summary Synthesis:** Drafted a concise one-paragraph summary detailing top revenue drivers, seasonal velocity, and strategic recommendations for stakeholders.
5. **Report Generation:** Compiled the final findings into an executive 2-page PDF report matching project visual standards.

## Files in this Repository
- `Retail_Sales_Analysis_Completed.xlsx` — Excel workbook containing raw data, working formulas, PivotTables, and summary
- `Task5_Excel_Data_Analysis_Report.pdf` — Executive 2-page visual PDF report
- `README.md` — This documentation write-up

## Outcome
The final Excel model and executive report deliver clear, data-driven recommendations regarding inventory timing, B2B customer targeting, and regional market expansion.
