#  Credit Card Financial Analytics Dashboard

An end-to-end **Data Analytics and Business Intelligence** project that analyzes credit card customer behavior, transaction patterns, and revenue generation using **Python, MySQL, SQL, Power BI, Power Query, and DAX**.

The project demonstrates the complete analytics workflow—from raw data preprocessing and database management to interactive dashboard creation and business insight generation.



#  Project Overview

Banks generate millions of credit card transactions every day. Understanding customer spending behavior, revenue generation, credit utilization, and customer demographics is essential for making informed business decisions.

This project transforms raw credit card datasets into meaningful business insights by building an interactive Power BI dashboard backed by Python preprocessing and MySQL database management.



#  Business Objectives

- Analyze customer demographics and spending behavior
- Monitor revenue generation across different customer segments
- Track transaction amount and transaction volume
- Compare performance of different card categories
- Analyze expenditure types
- Measure customer acquisition cost
- Evaluate customer credit utilization
- Monitor quarterly and weekly business performance
- Build an interactive dashboard for business decision-making



#  Tech Stack

## Programming

 Python
   Pandas
   NumPy

## Database

MySQL
 SQL

## Business Intelligence

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)

## Visualization

- KPI Cards
- Bar Charts
- Line Charts
- Matrix Tables
- Donut Charts
- Slicers
- Interactive Filters

## Version Control

- Git
- GitHub



#  Project Workflow


Raw CSV Files
      │
      ▼
Python Data Cleaning
      │
      ▼
MySQL Database
      │
      ▼
SQL Data Analysis
      │
      ▼
Power BI
      │
      ▼
Power Query
      │
      ▼
Data Modeling
      │
      ▼
DAX Calculations
      │
      ▼
Interactive Dashboard
      │
      ▼
Incremental Data Refresh
```



#  Dataset

The project consists of **four datasets**.

| Dataset | Description |
|----------|-------------|
| customer.csv | Customer demographic information |
| credit_card.csv | Credit card transaction details |
| cust_add.csv | Additional customer records used for incremental refresh |
| cc_add.csv | Additional transaction records used for incremental refresh |



#  Python Data Cleaning

Python was used for preprocessing and cleaning the raw datasets before loading them into MySQL.

## Data Cleaning Tasks

- Data inspection
- Missing value handling
- Duplicate checking
- Data type validation
- Date formatting
- Data consistency checks
- Exporting cleaned datasets

Libraries Used

- Pandas
- NumPy

---

# 🗄 MySQL Database

The cleaned datasets were imported into MySQL for structured storage and querying.

### SQL Operations Performed

- Database Creation
- Table Creation
- Data Import
- Aggregate Queries
- Filtering
- Sorting
- Group By
- Joins
- Business Analysis Queries



#  Power BI Dashboard

The project consists of two dashboards.

## Customer Dashboard

### KPIs

- Total Revenue
- Total Interest Earned
- Customer Satisfaction Score
- Total Income

### Visualizations

- Revenue by Age Group
- Revenue by Gender
- Revenue by Education
- Revenue by Marital Status
- Revenue by Occupation
- Revenue by Income Group
- Revenue by State
- Customer Distribution

---

## Transaction Dashboard

### KPIs

- Total Revenue
- Total Transaction Amount
- Total Transaction Count
- Total Interest Earned

### Visualizations

- Revenue by Card Category
- Revenue by Expenditure Type
- Revenue by Chip Usage
- Quarterly Revenue Trend
- Weekly Revenue Trend
- Customer Acquisition Cost
- Revenue by Customer Job
- Revenue by Education Level

---

# 📐 DAX Calculations

Custom calculated columns and measures were created using DAX.

Examples include:

- Revenue
- Age Group
- Income Group
- Weekly Revenue
- Quarterly Revenue
- Revenue Growth
- Customer Segmentation
- Financial KPIs

---

# 💰 Revenue Calculation

Revenue is calculated as:

```
Revenue =
Annual Fees
+ Interest Earned
+ Total Transaction Amount
  

Revenue represents the total business value generated through:

- Credit Card Annual Fees
- Interest charged on revolving balances
- Customer spending volume

---

#  Key Performance Indicators (KPIs)

- Total Revenue
- Total Transaction Amount
- Total Transaction Count
- Total Interest Earned
- Total Revolving Balance
- Average Utilization Ratio
- Customer Satisfaction Score
- Customer Acquisition Cost
- Total Income



#  Incremental Data Refresh

The project also includes additional datasets:

- cc_add.csv
- cust_add.csv

These datasets simulate new incoming business data and demonstrate incremental data loading. New customer and transaction records can be added without rebuilding the dashboard, allowing Power BI to refresh and display updated business insights.



#  Business Insights

Some key insights derived from the dashboard include:

- Blue Credit Cards generate the highest revenue.
- Bills and Entertainment contribute the highest spending.
- Customers aged 40–50 years contribute the highest revenue.
- Graduate customers are the largest revenue contributors.
- Self-employed customers generate significant business revenue.
- Swipe transactions are more common than Chip and Online transactions.
- States like Texas, California, and New York contribute the largest share of revenue.
- Higher credit utilization generally leads to increased interest revenue for the bank.






#  Skills Demonstrated

- Python
- Pandas
- NumPy
- SQL
- MySQL
- Power Query
- DAX
- Data Cleaning
- Data Wrangling
- Data Modeling
- Business Intelligence
- Data Visualization
- KPI Development
- Financial Analytics
- Customer Segmentation
- Exploratory Data Analysis (EDA)
- Dashboard Design
- Git
- GitHub



#  Future Enhancements

- Customer Churn Prediction using Machine Learning
- Credit Risk Analysis
- Fraud Detection Dashboard
- Customer Lifetime Value (CLV) Prediction
- Time-Series Revenue Forecasting
- Automated ETL Pipeline
- Real-Time Dashboard Integration



#  Dashboard Preview

## Customer Dashboard





## Transaction Dashboard



#  Author

Romil Kumar

Computer Science Engineering Student | Data Analytics Enthusiast

### Connect with Me

- GitHub: https://github.com/RomilKumar
- LinkedIn: https://www.linkedin.com/in/romil-kumar-842a55282/
- Email: romilkumar13@gmail.com
