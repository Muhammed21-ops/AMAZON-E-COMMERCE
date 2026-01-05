# Amazon E-Commerce Analytics Dashboard (Power BI)

## Project Overview
This project is a **customer-facing, decision-oriented Power BI dashboard** designed to analyze the performance of an Amazon-style e-commerce business.  
The focus is not only on visualization, but on **data modeling, performance optimization, and actionable insights**.

The dashboard is built to support **executive, operational, and analytical decision-making** through dynamic KPIs, time intelligence, and performance diagnostics.

---

## Key Objectives
- Monitor **Sales, Profit, Orders, Customers, and Quantity**
- Analyze **regional, segment, and category performance**
- Track **time-based trends** (MoM, PM, QTD)
- Identify **loss-making operations and operational risks**
- Support **target vs actual** performance analysis
- Deliver a **clean, customer-ready dashboard** without exposing formulas or model logic

---

## Data Model & Architecture
- **Star Schema** data model
  - Fact table: Orders / Sales transactions
  - Dimension tables: Date, Product, Customer, Region, Segment
- Dedicated **Date table**
  - Marked as Date Table
  - Used for all time intelligence calculations
- Clean separation between:
  - Base measures
  - Calculation logic
  - Visual layer

This structure ensures **scalability, maintainability, and performance**.

---

## Calculation Groups (Advanced Feature)
The dashboard uses **Calculation Groups** to avoid measure duplication and ensure consistency across KPIs.

### Time Intelligence Calculation Group
Dynamic time analysis applied to all base KPIs:
- Current Measure
- Previous Month (PM)
- Month-over-Month (MoM)
- MoM %
- Quarter-to-Date (QTD)

This allows switching time perspectives **without creating separate measures for each KPI**.

---

## KPIs & Metrics
- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Quantity Sold
- Loss-Making Orders
- Balance (Closing Balance by Month)
- On-Time Delivery Performance
- Delivery Delay %

KPIs are designed with **conditional formatting** to highlight risks and opportunities instantly.

---

## Performance Considerations
- Measure count optimized using Calculation Groups
- Avoided unnecessary visual complexity
- Conscious handling of **render vs DAX performance**
- Conditional formatting applied only where it adds analytical value

The result is a dashboard that remains **responsive even with complex logic**.

---

## Dashboard Pages
- **Executive Overview**
  - High-level KPIs and trends
- **Customer Analysis**
  - Segment and gender distribution
  - Customer behavior insights
- **Product Analysis**
  - Category and product performance
- **Target & Performance**
  - Target vs Actual
  - Profit forward and achievement analysis
- **Advanced Analysis**
  - Regional MoM & QTD analysis
  - Loss-making vs profitable operations
  - Outlier and distribution diagnostics

---

## Intended Use
- Executive reporting
- Operational performance monitoring
- Client-facing analytics


The dashboard is suitable for **Power BI Embedded or secure customer sharing** scenarios.

---

## Tools & Technologies
- Power BI Desktop
- DAX (Advanced Measures & Calculation Groups)
- Data Modeling (Star Schema)
- Performance-oriented dashboard design# AMAZON-E-COMMERCE
AMAZON E-COMMERCE DASHBOARD ANALYSIS
