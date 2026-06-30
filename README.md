# 📊 Quality Claims Analytics End-to-End

---

## 🔍 Overview
This project presents an end-to-end data analytics solution focused on quality claims. It integrates **data preprocessing, relational modeling, SQL analysis, and business intelligence dashboards** to identify patterns, root causes, and operational improvement opportunities.

The solution demonstrates how raw operational data can be transformed into actionable insights through a structured and reproducible analytics pipeline.

---

## 🎯 Business Problem
Organizations managing industrial operations and supply chains need to monitor quality-related incidents (claims) effectively.

However:
- Data is fragmented across sources 
- Root causes are not systematically analyzed 
- Decision-making is reactive rather than proactive 

The key challenge is:

> **How to identify the main drivers of quality issues and prioritize corrective actions based on data.**

---

## 💡 Business Impact
This solution enables:

- Improved visibility into quality performance 
- Identification of high-impact root causes 
- Reduction of manual reporting effort 
- Faster and more informed decision-making 
- Prioritization of corrective actions 

Ultimately, it supports:
- Cost reduction 
- Operational efficiency 
- Improved product quality 

---

## 🏭 Business Context
The project is inspired by industrial environments where quality events impact:
- Manufacturing processes 
- Supply chain operations 
- Customer satisfaction 

It reflects real-world scenarios such as:
- Supplier-related issues 
- Process deviations 
- Logistics and handling damages 
- Data entry and operational errors 

---

## ⚠️ Data Disclaimer
The dataset used in this project is **synthetic and generated for demonstration purposes only**.

- It does not represent real company data 
- It is designed to simulate realistic industrial scenarios 
- It includes controlled correlations to enable meaningful analysis 

---

## 📊 Dashboard Overview

The Power BI dashboard is structured into four main analytical views:

### 1. Executive Overview
- Total claims 
- Total cost impact 
- Average days to close 
- Recurrence rate 
- Time trend analysis 

### 2. Root Cause Analysis
- Pareto of root causes 
- Cost distribution by cause 
- Severity breakdown 

### 3. Segmentation Analysis
- Claims by customer 
- Claims by product family 
- Claims by supplier and location 

### 4. Action Prioritization
- Top focus areas 
- High impact + high recurrence issues 
- Aging claims 

---

## 🚀 Key Features
- End-to-end data pipeline (Python → SQL Server → BI) 
- SQL-based data modeling (star schema) 
- Data quality preprocessing 
- Root cause and Pareto analysis 
- Time series and trend analysis 
- Action-oriented insights and prioritization 

---

## 🏗️ Data Modeling and Architecture

### Architecture Flow
CSV Raw Data ↓ Python Preprocessing ↓ SQL Server Database ↓ SQL Queries & Analytics ↓ Power BI Dashboard

### Data Model A star schema is used: 
- **Fact Table**
- `fact_quality_claims`
- **Dimension Tables**
- `dim_customer` 
- `dim_product` 
- `dim_supplier` 
- `dim_root_cause` 
- `dim_location` 
- `dim_date`
  
This structure enables: 
- Scalable analytics -
- Efficient querying -
- Flexible dashboard design
  
---

## 🔬 Analysis and Methodology The analysis follows a structured approach: 

### Data Preparation 
- Cleaning raw CSV data using Python
- Handling missing values and data types
- Removing duplicates
- Validating categorical values

### Data Loading
- Data loaded into SQL Server using `BULK INSERT`
- Tables created with controlled data types
- Referential structure maintained 

### SQL Analysis 
- KPI calculation
- Root cause Pareto analysis
- Trend analysis (monthly, YoY/MoM)
- Segmentation (customer, product, supplier)
- Prioritization logic ### Business Interpretation
- Insights translated into operational recommendations
- Focus on decision-making and actionability 

--- 

## 📈 Key Insights 
- A small number of root causes explain the majority of cost impact
- Critical severity claims have longer resolution times
- Certain product families show higher recurrence rates
- A limited subset of customers contributes to most escalations
- Specific suppliers are associated with higher defect levels 

--- 

## 🛠️ Tools and Technology 
- **Python** - pandas - numpy
- **SQL Server** - relational database - BULK INSERT - SQL queries
- **Power BI** - data visualization - dashboards
- **GitHub** - version control - project documentation 

--- 

## 🚀 Future Improvements 
- Implement incremental data loading using MERGE
- Automate pipeline execution (scheduled jobs)
- Add predictive models for defect detection
- Integrate real-time data sources
- Extend dashboard with advanced analytics 

--- 

## 💼 Key Skills Demonstrated 
- Data cleaning and preprocessing
- SQL and relational data modeling
- Data pipeline design (ETL concepts)
- Business intelligence development
- Analytical thinking and problem solving
- Translation of data into business insights 

--- 

## 📝 Notes This project was developed as a **portfolio initiative to bridge industrial domain knowledge with data analytics capabilities**. It emphasizes: 
- Real-world applicability
- Structured analytical thinking
- Business-oriented decision support The goal is not only to showcase technical skills but also the ability to **solve business problems using data**.

