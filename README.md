# Maven Market Power BI Dashboard

A retail sales performance dashboard built on the Maven Market sample dataset (1997-1998
transactions, customers, products, and store data), built through a guided Business
Intelligence training course to practice data modeling, DAX, and visualization design.

![Topline Performance](screenshots/topline-performance.png)
*(add a screenshot here — see "Screenshots" below)*

## Report pages

- **Topline Performance** — KPIs, trends, and category/store performance via column
  charts, gauges, a map, and a pivot table
- **Notes** — report documentation page

## Skills demonstrated

- **Data modeling**: relationships across transactions, customers, products, stores,
  regions, and calendar tables
- **DAX**: KPI and trend measures, plus a self-documenting **Data Dictionary** measure
  that uses `INFO.VIEW.COLUMNS()`, `INFO.VIEW.MEASURES()`, `INFO.VIEW.TABLES()`, and
  `INFO.VIEW.RELATIONSHIPS()` to auto-generate a live table of every column, measure,
  table, and relationship in the model directly from the data model's own metadata —
  a model-documentation technique that keeps itself up to date as the model changes.
- **Visualization design**: KPI cards, gauges, column charts, treemaps, maps, pivot tables

## About this project

This report was built by following a structured Power BI for Business Intelligence course,
using the standard Maven Market sample dataset. The course provided the raw dataset and
exercise structure; the data model, DAX measures, and report design were built hands-on
by following and applying each stage of the course. The raw dataset is not included here,
as it's the training provider's own content — only the finished `.pbix` report, which is
the work product, is included.

## Opening the report

Requires [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) to open
`pbix/Maven_Market_Report_COMPLETE.pbix` and interact with the report directly.

## Screenshots

*(Add a screenshot of the Topline Performance page here — export from Power BI Desktop
via File > Export > Export to PDF, then screenshot the page, or use "Copy as image" on
the page/visual. Save it in a `screenshots/` folder and reference it in this README.)*
