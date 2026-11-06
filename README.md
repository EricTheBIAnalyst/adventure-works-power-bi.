ADVENTURE WORKS SALES ANALYTICS | POWER BI

An end-to-end Power BI report that turns eight raw CSV files into one interactive reporting solution for a global cycling equipment manufacturer. It tracks sales, revenue, profit and returns across products, customers and sales territories.

![Executive Dashboard](images/01-executive-dashboard.png)

BUSINESS PROBLEM

Adventure Works manufactures cycling equipment and accessories and sells globally. Management lacked a unified view of key performance indicators. They needed to track sales, revenue, profit and returns, compare regional performance, analyze product trends and identify high-value customers.

The data sat in multiple CSV files, which made reporting slow and limited data-driven decisions.

WHAT I DID

Using Power BI Desktop, I built a complete BI solution:

- Connected and transformed 8 raw CSV datasets using Power Query
- Cleaned and standardized transaction, product, customer, returns and territory data
- Designed a Snowflake Schema data model for scalable reporting
- Wrote 20+ DAX measures for revenue, profit, return rates, customer metrics and time-based performance
- Built a 4-page interactive report with drillthrough, custom tooltips, navigation buttons and dynamic slicers

REPORT PAGES

| Page | Purpose |
|------|---------|
| Executive Dashboard | High-level view of sales, revenue, profit and returns |
| Product Performance | Top and bottom products and categories, and product trends |
| Customer Insights | High-value customers and revenue contributors |
| Geographic Sales | Performance by sales territory and region |

![Product Performance](images/02-product-performance.png)
![Customer Insights](images/03-customer-insights.png)
![Geographic Sales](images/04-geographic-sales.png)

DATA MODEL

The model follows a Snowflake Schema, with a central sales fact table connected to dimension tables for products, customers, territories and dates, and a returns table linked to the same dimensions.

![Data Model](images/05-data-model.png)

KEY INSIGHTS

- Identified the top-performing products and categories driving revenue growth
- Highlighted high-performing and underperforming sales territories
- Enabled customer-level analysis to find high-value customers and revenue contributors
- Improved visibility into sales, profit and return trends across the business
- Gave executives and operational teams one interactive place to monitor and explore performance

PROJECT METRICS

- 8 integrated data sources
- Snowflake Schema data model
- 20+ DAX measures
- 4 interactive report pages
- Drillthroughs, custom tooltips and dynamic filtering

TOOLS USED

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data modeling
- Snowflake Schema design

REPOSITORY STRUCTURE

```
adventure-works-power-bi/
├── README.md
├── AdventureWorks_Sales_Report.pbix
├── data/                  (the 8 raw CSV files)
├── images/                (dashboard and data model screenshots)
└── dax/
    └── measures.md        (DAX measures used in the report)
```

HOW TO OPEN THIS PROJECT

1. Download or clone this repository.
2. Install Power BI Desktop (free, Windows).
3. Open AdventureWorks_Sales_Report.pbix.
4. If Power BI shows a data source error, go to Home > Transform data > Data source settings, choose Change Source, and point each file to your local data folder.
5. Click Refresh to load the data.

LOOKING FOR SIMILAR RESULTS?

If your business relies on spreadsheets or disconnected data sources, I can build a Power BI system like this one, combining data modeling, KPI development and dashboard design so you can track performance and make faster decisions.

Eric Kyuma | Business Intelligence and Data Analyst | Nairobi, Kenya
- LinkedIn: [add your LinkedIn URL]
- Portfolio: [Maven Showcase](https://mavenshowcase.com/profile/0841f340-7091-70d6-4153-097ec33884f7)
- Message me on LinkedIn with what you're working with.
