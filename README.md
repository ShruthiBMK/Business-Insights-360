# Business-Insights-360
Created a fully functional PowerBI Dashboard for Data Driven Decisions, which gives insights on various departments like Finance, sales, marketing and Supply chain.

## Project Overview

AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement the data analytics using PowerBI in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project is hoped to give answers to the questions of stakeholder in terms all the aspects like finance, sales, marketing and supply chain.
## Tech stacks
- SQL
- PowerBi Desktop
- Excel
- DAX 
- DAX studio (for optimizing the report)

### PowerBI Dashboard

* Connected Power BI to MySQL and Excel, transformed data by establishing a data pipeline (ETL) using Power Query, Data Modelling to establish relations by snowflake schema and initial Data validation was done against benchmark values.
* Utilized DAX to create calculated columns and measures, and built a dynamic dashboard with KPI’s for sales, finance, marketing, and supply chain.
* Published a report on Power BI service for user acceptance testing (UAT).
* Incorporated stakeholder feedback to create an Executive Dashboard, resolved quality issues, optimized dashboard performance, and deployed the dashboard to Power BI service with gateway setup to MySQL Database and local Excel files for Automatic Data Refresh.
* Designed a 3-level analytical dashboard enabling stakeholders to drill into top products, markets, and customers — tracking P&L trends, % changes, and supply chain forecast accuracy to improve inventory management and business performance.
### [To view Live Dashboard click here](https://app.powerbi.com/view?r=eyJrIjoiYWY1YzQyYTgtMDhkNy00NGYxLTlkYjYtYzMyODE4N2E1ZWZiIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=5a6be796eac0aa9a19e4 )

## Key Features in Finance View:
* The profit and loss Statement, explains on varoius P&L Metrics form Gross Sales to Net Profit. BM indicates the  benchmark , which is Either Last year or the Target.    which can be selected through the slicer provided.
* KPI’s for Net Sales, Gross Margin %, Net Profit %.
* Net sales Performance Trend in comparision with Target/Last Year which can be selected Dynamically.
* Top/Bottom Product and Top/Bottom Customers based on Net Sales.

## Key Features in Sales View:
* Unit Economics 1: Net Sales vs Total Post Invoice Discount Amount and Pre-Invoice Discount Amount given by the Company.
* Unit Economics 2: Total Cost of Goods Sold (COGS) spent by the Company and then finally got the actual Gross Margin.
* Customer and Product Performance analysis based on Net Sales, Gross Margin and Gross Margin %.
* Performance Matrix analysis for Market, Customer and Region based on Net Sales and Gross Margin %.
* Sales Trend Tooltip for every single Customer based on Net Sales and Gross Margin %.

## Key Features in Marketing View:
* Unit Economics: There are some Operational Expenses spent for Product. After subtracting this Expenses got the actual scenario of Net Profit.
* Performance Matrix analysis for Segment, Category and Product based on both “Net Sales & Net Profit %” and “Net Sales & Gross Margin %” by using a dynamic toggle button.

## Key Features in Supply Chain View:
* KPI’s for Forecast Accuracy, Net Error, ABS Error.
* Risk Factor analysis.
* Accuracy vs Net Error Trend analysis.
* Key Metrics for both Customer and Products based on FA%, FA% LY, Net Error, Net Error%, Risk Factor.

## Key Features in Executive View:
Report Page for the Top Level Management of the Company who want to check on all key metrics and KPI's.
* Market Share Trend analysis for AtliQ and other competitors.
* Revenue analysis by Division and Channel.
* Top 5 Products and Top 5 Customers by Revenue.
