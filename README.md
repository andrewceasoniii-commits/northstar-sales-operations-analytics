# Northstar Commercial Solutions  
## Sales Operations & Performance Analytics Project

### Project Overview
Northstar Commercial Solutions (NCS) is a fictional mid-market B2B SaaS and professional services company.  
This project simulates a real-world **Sales Operations Analytics** environment and demonstrates how data can be used to support business decision-making, performance tracking, and operational insights.

The goal of this project is to:
- Integrate data from multiple business domains
- Analyze sales performance trends over time
- Identify drivers behind revenue growth and shortfalls
- Deliver actionable insights through structured analysis and dashboards

---

## Business Context
Northstar sells:
- Subscription-based analytics software
- SaaS add-on modules
- Professional implementation services

Sales leadership wants to understand:
- Revenue performance vs. targets
- Regional and sales rep performance
- Product adoption trends
- The impact of growth, churn, and sales ramp-up over time

---

## Dataset Overview
The dataset spans **January 2020 – December 2024** and reflects realistic business growth and operations.

### Data Model
This project uses a **star-schema-friendly structure**:

- **Fact Tables**
  - `fact_sales.csv` – transactional sales data
  - `fact_sales_targets.csv` – monthly revenue targets by region

- **Dimension Tables**
  - `dim_customers.csv`
  - `dim_products.csv`
  - `dim_sales_reps.csv`
  - `dim_regions.csv`

---

## Key Data Statistics
- **Time span:** 2020–2024 (5 years)
- **Customers:** 420 total (363 active at end of 2024)
- **Sales orders:** ~20,000 transactions
- **Sales reps:** 28 (includes hires and turnover)
- **Regions:** Midwest, Northeast, South, West

The data includes:
- Customer growth and churn
- Sales rep ramp-up and turnover
- New product launches
- Seasonal trends and anomalies
- Revenue targets vs. actuals

---

## Key Metrics & KPIs
This dataset supports analysis of:
- Total Revenue
- Revenue vs. Target
- Month-over-Month and Year-over-Year Growth
- Sales Rep Performance
- Regional Performance
- Product Mix and Margin
- Customer Retention and Expansion

---

## Tools Used
- **Excel / CSV** – data storage and validation
- **SQL** – querying, joins, and aggregations
- **Tableau** – interactive dashboards and visual analysis
- **GitHub** – project versioning and documentation

---

## Example Business Questions Answered
- Which regions consistently miss revenue targets?
- How does sales rep tenure impact performance?
- Which products drive the highest margin?
- What caused revenue slowdowns during specific periods?
- How did new product launches affect revenue mix?

---

## Project Structure
