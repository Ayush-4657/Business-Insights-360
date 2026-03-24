# Business-Insights-360

## Overview

AtliQ Hardware, a rapidly expanding company specializing in computers and accessories, faced unexpected losses after launching its store in America. Recognizing the need for advanced analytics to gain a competitive edge, AtliQ decided to implement Power BI for insights into finance, sales, marketing, and supply chain operations. This project delivers a comprehensive analytics solution to empower data-driven decision-making across the organization.

This project was completed as part of the Codebasics Power BI Course, which provided comprehensive guidance and practical insights into building analytics solutions.

## Explore the live dashboard here - [Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiZmIzOWJlMTMtMTY1YS00NmI2LWIzNmUtMTM2M2U2NDgyYmVkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Objectives
1. Enable stakeholders to make informed decisions across finance, sales, marketing, and supply chain domains.
2. Leverage Power BI to visualize and analyze data for actionable insights.
3. Develop a robust data model to ensure efficient report performance.

## Datasets

### gdb041
- dim_customer: Contains static customer details.
- dim_market: Static data on market segments.
- dim_product: Product details.
- fact_forecast_monthly: Forecasted customer needs for better warehouse management and cost reduction.
- fact_sales_monthly: Contains actual sold quantities, replacing forecast values.

### gdb056
- freight_cost: Costs associated with freight.
- gross_price: Gross pricing details.
- manufacturing_cost: Production cost details.
- pre_invoice_deductions: Deductions applied before invoicing.
- post_invoice_deductions: Deductions applied after invoicing.

## Data Processing Workflow

- **Data Extraction:** Data imported from MySQL into Power BI.
- **Data Cleaning:** Removed inconsistencies and ensured data quality.
- **Data Modeling:** Followed the Snowflake schema for optimal performance.
- **Data Analysis:** Built insights using calculated columns, DAX measures, and visualizations.

## Power BI Dashboard Overview
The dashboard consists of Five interactive pages:

**1. Finance View:**
- Profit and Loss statements.
- Top and Bottom Products and Customers by Net Sales.
- Budgeting and cost control insights.
<img width="1444" height="811" alt="Finance View" src="https://github.com/user-attachments/assets/ef975aa5-70ce-451b-9f5b-9e75d33614f0" />
---

**2. Sales View:**
- Customer performance by Net Sales.
- Gross Margin and Gross Margin %.
- Revenue trends and market share analysis.
<img width="1444" height="812" alt="Sales View" src="https://github.com/user-attachments/assets/4a2f1e6b-dfc4-4949-944e-e059d8bd1598" />

**3. Marketing View:**
- Segment performance by Gross Margin % and Net Profit %.
- Customer engagement and brand visibility metrics.
<img width="1446" height="816" alt="Marketing View" src="https://github.com/user-attachments/assets/cc6b1ea1-9bab-4529-94fc-a785575e1c2b" />


**4. Supply Chain View:**
- Forecast accuracy and Net error metrics.
- Inventory and supplier performance analysis.
<img width="1443" height="812" alt="Supply Chain View" src="https://github.com/user-attachments/assets/7b004e42-60d7-4630-b207-721ae10f4981" />


**5. Executive View:**
- High-level KPIs like Net Sales, Gross Margin %, and Net Profit %.
- Performance by channel and sub-region.
- Highlights of top customers and products.
<img width="1447" height="813" alt="Executive View" src="https://github.com/user-attachments/assets/24200945-c99b-4a47-a682-94d462b2919e" />


## Tools Used
**Power BI:** Visualization and reporting.
**SQL:** Data extraction and preparation.
**DAX:** Custom measures and calculated columns.
**DAX Studio:** Performance optimization.

## Conclusion
This project demonstrates the power of analytics in addressing business challenges and improving profitability. By leveraging Power BI, AtliQ Hardware is now equipped to make informed decisions, answer key business questions, and maintain a competitive edge in the market.
