# 02 – Retail Analysis Report

## Goal
Practise building interactive report pages in Power BI Desktop: choosing visuals,
adding slicers, drill-through, and conditional formatting.

## Note on the file
`Retail_Analysis_Sample.pbix` is Microsoft's Retail Analysis sample, which ships with
pre-built pages (such as Overview). The five pages below are the ones I built.

## Pages I built

**KPI** – This year vs. last year units by fiscal month. I sorted the chart before
converting it to a KPI visual, since the KPI visual can't be sorted.
![KPI](screenshots/KPI.png)

**Reg vs Markdown** – Pie chart of regular vs. markdown sales units, with sales dollars
added as tooltips.
![Reg vs Markdown](screenshots/Reg_vs_Markdown.png)

**TY, LY and Variance** – Clustered columns comparing this year, last year, and variance
by chain, with data labels and a table using a colour scale to flag this year's sales.
![TY LY Variance](screenshots/TY_LY_and_Markdown.png)

**Sales by Category** – Stacked bar of this year's sales by category with Chain and
Buyer dropdown slicers.
![Sales by Category](screenshots/Sales_by_Category.png)

**Drill Through Analysis** – A multi-row card page that opens when you right-click a
category on Sales by Category, filtered to that category. Includes a custom back button.
![Drill through](screenshots/Drill_Through_Analysis.png)

## Also done
- Synced a Chain slicer across pages
- Applied a colourblind-safe theme

## Scope
Done in Power BI Desktop. Publishing and dashboards were not practised.

## Files
- [`Retail_Analysis_Sample.pbix`](./Retail_Analysis_Sample.pbix)