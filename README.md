# AdventureWorks Business Intelligence Dashboard

## Overview
This project delivers a comprehensive Power BI dashboard for AdventureWorks, a global manufacturing company specializing in cycling equipment. The dashboard enables data-driven decision-making by tracking KPIs, analyzing sales trends, and evaluating customer and product performance across time and geography. It incorporates advanced metrics such as Monthly Recurring Revenue (MRR) and Average Revenue per Customer (ARPC) to align with strategic business goals.

---

## Business Context

### Problem
Traditional static reports limited sales visibility and hindered performance tracking.

### Objective
To develop a dynamic, interactive dashboard for real-time monitoring of sales effectiveness, customer behavior, and revenue trends, while improving reporting efficiency and executive decision-making.

---

## Key Features & Insights

### Data Analysis
- **Sales Trends:** Monthly and annual performance insights
- **Customer Insights:** High-value customer segmentation
- **Product Analysis:** Top-selling products by category
- **Geographical Distribution:** Regional performance mapping
- **Budget Comparison:** Actual vs. 2021 budget performance

### Business Metrics
- **Total Sales vs. Budget:** Gap analysis
- **Monthly Recurring Revenue (MRR):** Evaluate repeatable income streams
- **Average Revenue Per Customer (ARPC):** Identify high-value segments
- **Return Rates & Profitability:** Operational performance indicators

---

## Tools & Technologies

- **Power BI Desktop** for dashboard development and visualization
- **SQL Server Management Studio (SSMS)** for data extraction and cleaning
- **Power Query Editor** for transformation and modeling
- **DAX (Data Analysis Expressions)** for calculated measures and KPIs
- **Microsoft Excel & CSVs** for data export and integration

---

## Technical Implementation

### Data Preprocessing
- Restored the `AdventureWorksDW2019` database in SQL Server
- Cleaned and filtered sales, customer, and product tables
- Exported structured data into CSV format for Power BI integration

### SQL Transformations
- **Calendar Table:** Standardized time dimensions
- **Customer Table:** Enriched with geographic info
- **Sales Table:** Aggregated internet sales
- **Product Table:** Cleaned product hierarchy

### Power BI Model
- Loaded CSVs into Power BI
- Established relationships among fact and dimension tables
- Designed interactive dashboard views with slicers and filters

---

## Business Impact

- **Improved Sales Monitoring:** Real-time KPI updates and alerting
- **Enhanced Decision-Making:** Data-driven insights for strategy
- **Optimized Resource Allocation:** Focus on top-performing segments
- **Strategic Budgeting:** Better forecasting with ARPC & MRR integration

---

## Results

- Real-time visual tracking of sales performance
- Clear visibility into budget vs. actual sales
- Identification of top 10 products and customers
- Recurring revenue insights (MRR & ARPC)

---

## Business Recommendations

- **Optimize Sales Strategy:** Focus on high-margin products and key customers
- **Enhance Forecasting:** Leverage ARPC and MRR for precision planning
- **Target Geographic Expansion:** Identify and invest in high-performing regions

---

## Dependencies

- Power BI Desktop
- Microsoft SQL Server
- AdventureWorksDW2019 Database

---

## Acknowledgments
This project was inspired by Power BI training modules and case-based learning resources. Built for learning purposes.

