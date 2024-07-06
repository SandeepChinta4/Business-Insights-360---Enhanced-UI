# Business Insights 360 - Enhanced UI

## Project Overview

AtliQ Hardware is rapidly expanding and has decided to implement data analytics using Power BI to stay ahead of competitors and make data-driven decisions. This project addresses stakeholder questions across finance, sales, marketing, and supply chain. The project followed the Codebasics Power BI Course.

[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiYzVkMTMzNGYtNDMwZi00Zjk1LTlhMDAtZGViZjcxYTE3M2Q1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Tech Stack

- SQL
- Power BI Desktop
- Excel
- DAX
- DAX Studio
- Project Charter File

## Enhancements

### Redesigned UI

- Eye-catching visuals and layouts
- Improved user experience with intuitive navigation
- Modern design elements for a professional look

### Advanced Filtering

- Parameters and filters for clearer data insights
- Interactive visuals for detailed analysis
- Dynamic titles and KPIs based on applied filters

## Power BI Techniques Learned

- Project scoping questions
- Calculated columns and measures using DAX
- Data modeling
- Bookmarks for visual switching
- Page navigation with buttons
- Zero division error prevention
- Creating date tables with M language
- Dynamic titles based on filters
- KPI indicators
- Conditional formatting
- Data validation
- Power BI services: publishing, personal gateway setup, app creation, collaboration, workspace, and access permissions

## Key Business Terms

- Gross Price
- Pre-Invoice Deductions
- Post-Invoice Deductions
- Net Invoice Sale
- Gross Margin
- Net Sales
- Net Profit
- COGS (Cost of Goods Sold)
- YTD (Year to Date)
- YTG (Year to Go)
- Direct, Retailer, Distributors
- Consumer

## Company Background

AtliQ Hardware sells computers and accessories globally through retailers, direct sales, and distributors. Recently, the company faced losses due to non-data-driven decisions and competitors' strong analytics teams. To survive and thrive, AtliQ Hardware is building an analytics team for future insights and decisions.

## Initial Project Questions

- Project objectives and success metrics
- Timeline and preview expectations
- Stakeholder hopes, fears, and usage
- Design and view inputs
- Resources and data needs
- Potential project risks

## Dataset Understanding

### Dimension Tables

- **dim_customer:** 27 markets, 75 customers, 2 platforms (Brick & Mortar, E-commerce), 3 channels (Retailer, Direct, Distributors)
- **dim_market:** 27 markets, 7 sub-zones, 4 regions (APAC, EU, NAN, LATAM)
- **dim_product:** Divisions (P & A, PC, N & S), 14 categories, various variants

### Fact Tables

- **fact_forecast_monthly:** Forecasted customer needs, denormalized, start date of month
- **fact_sales_monthly:** Similar to forecast table, with sold quantity instead

### Other Tables

- **freight_cost:** Travel and other costs by market and fiscal year
- **gross_price:** Gross prices by product code
- **manufacturing_cost:** Manufacturing costs by product code and year
- **pre_invoice_deductions:** Pre-invoice deductions by customer and year
- **post_invoice_deductions:** Post-invoice and other deductions

## Data Import and Modeling

- Import datasets from MySQL to Power BI using database credentials
- Data modeling is crucial for performance; followed snowflake modeling method

### Dashboard designing

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

## Home view

![1 Home](https://github.com/SandeepChinta4/Business-Insights-360---Enhanced-UI/assets/137393739/f1749956-dccb-4600-b256-49535a8299f7)

## Finance View

![2 Finance](https://github.com/SandeepChinta4/Business-Insights-360---Enhanced-UI/assets/137393739/d4c15720-4b2b-410c-8e14-bf7138cf5a73)

## Sales View

![3 Sales](https://github.com/SandeepChinta4/Business-Insights-360---Enhanced-UI/assets/137393739/7bc47b27-21b7-4885-ada4-a791b0201520)

## Marketing View

![4 Market](https://github.com/SandeepChinta4/Business-Insights-360---Enhanced-UI/assets/137393739/25e18e0e-a6b5-4850-9a8e-4020a8550aa0)

## Supply chain View

![5 Supply Chain](https://github.com/SandeepChinta4/Business-Insights-360---Enhanced-UI/assets/137393739/831d466f-c949-4906-9d8d-5e0aa1ac78fc)

## Executive View

![6 Executive](https://github.com/SandeepChinta4/Business-Insights-360---Enhanced-UI/assets/137393739/4f40ff7e-88ce-4980-aefc-2aaa571c2cf7)

## Project Outcome

- Enhanced data visualization and user experience
- Improved decision-making through clear and interactive dashboards
- Increased stakeholder satisfaction with data-driven insights
- Optimized report performance and usability with advanced filtering and dynamic elements
- Established a robust analytics foundation for future projects and decision-making
