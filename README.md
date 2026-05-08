# NBFC Credit Risk & Portfolio Analytics Dashboard

## Overview

An end-to-end Power BI dashboard built to simulate real-world portfolio monitoring and credit risk analytics workflows used by NBFCs, fintech lenders, and lending businesses.

This project enables business, risk, and operations teams to monitor:

- Loan portfolio health
- Delinquency trends
- Portfolio at Risk (PAR)
- Collection efficiency
- Customer risk segmentation
- Employee productivity
- Geographic credit exposure

The objective was to transform raw lending data into actionable business intelligence for better decision-making.

---

## Business Problem

NBFCs handle large volumes of short-term and unsecured loans.

Without centralized analytics, organizations face challenges such as:

- Limited visibility into portfolio health
- Delayed identification of delinquent customers
- Weak monitoring of collection performance
- Poor understanding of risky customer segments
- Lack of regional portfolio risk insights

This dashboard solves these problems through an interactive risk and portfolio monitoring framework.

---

## Project Highlights

### Executive Portfolio Monitoring
- Total Loans
- Portfolio Disbursed
- Total Collection
- Outstanding Principal
- Active AUM
- Gross Receivables

### Credit Risk Analytics
- Portfolio at Risk 30+ (PAR30)
- Portfolio at Risk 60+ (PAR60)
- Average Days Past Due (DPD)
- Default Rate
- High Risk Customer Identification
- Risk Category Segmentation

### Collection Performance
- Collection Efficiency %
- Delinquency Distribution by DPD Bucket
- Active vs Closed Portfolio Analysis

### Operational Analytics
- Employee-wise Disbursal Performance
- Employee-wise Collection Performance

### Geographic Analytics
- Regional Delinquency Analysis
- Regional Portfolio Exposure

---

## Dashboard Architecture

## Page 1 — Executive Summary
Provides a high-level snapshot of portfolio performance.

Key KPIs:
- Total Loans
- Portfolio Disbursed
- Total Collection
- Collection Efficiency
- Outstanding Principal
- Default Rate
- Average Risk Index

---

## Page 2 — Portfolio Risk Analysis
Dedicated risk monitoring dashboard.

Includes:
- Delinquency Distribution by DPD Bucket
- Portfolio Risk Mix
- Channel-wise Portfolio Contribution
- Active vs Closed Portfolio
- PAR30 / PAR60 tracking

---

## Page 3 — Business Performance Analytics
Operational and business performance monitoring.

Includes:
- Employee Disbursal Leaderboard
- Employee Collection Performance
- Regional Delinquency Analysis
- Regional Portfolio Exposure

---

## Dataset & Data Preparation

### Data Sources
- Loan disbursal data
- Closed loan data
- Collection data
- Customer/CIBIL data

### Data Cleaning Performed
- Removed duplicates
- Standardized date formats
- Managed null values in Close Date for active loans
- Handled blank DPD buckets where DPD = 0
- Corrected data types
- Merged multiple raw files into final dataset

Final cleaned table:

`Portfolio_Final_Risk_Dataset`

---

## Data Modeling & DAX

### Calculated Columns
- Outstanding Amount
- Loan Status
- Risk Category
- DPD Bucket

### Key Measures
- Total Loans
- Portfolio Disbursed
- Total Collection
- Outstanding Principal
- Active AUM
- Gross Receivables
- Collection Efficiency %
- Default Rate
- PAR30
- PAR60
- Average DPD
- High Risk Customers

---

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Excel

---

## Business Impact

This dashboard helps lenders:

- Monitor portfolio quality in real time
- Detect delinquency early
- Improve collection tracking
- Identify high-risk customer segments
- Optimize regional lending strategies
- Improve operational decision-making

---

## Dashboard Preview

## Executive Summary
![Executive Summary](images/page1_executive_summary.png)

## Portfolio Risk Analysis
![Portfolio Risk Analysis](images/page2_risk_analysis.png)

## Business Performance Analytics
![Business Performance Analytics](images/page3_business_performance.png)

---

## Skills Demonstrated

- Business Intelligence
- Credit Risk Analytics
- Portfolio Monitoring
- Data Cleaning & Transformation
- Dashboard Design
- KPI Framework Design
- Financial Analytics
- DAX Measure Development

---

## About Me

Rohit Raj  
Data Analyst | Business Intelligence Analyst | Financial & Risk Analytics

Helping businesses transform raw data into decision-ready dashboards and analytics solutions using Power BI, SQL, Excel, and Python.

Core expertise:
- Credit Risk Analytics
- Portfolio Performance Monitoring
- Collections & Delinquency Analytics
- KPI Dashboard Development

## Connect With Me

- LinkedIn: [https://www.linkedin.com/in/rohitrajanalyticsmind/]
- GitHub: [https://github.com/RohitRa200/]
- Email: rohitrajrajrohit60@gmail.com
