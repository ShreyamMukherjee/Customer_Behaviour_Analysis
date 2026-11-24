# Customer Shopping Behaviour Analysis

An end-to-end data analytics project exploring customer purchasing patterns, product performance and shopping behaviour using Python, Pandas, NumPy, PostgreSQL, SQL and Microsoft Power BI.

## Project Overview

This project analyses a customer shopping behaviour dataset containing **3,900 records**. The objective is to understand customer demographics, purchasing patterns, product categories, subscription status and revenue trends.

The project follows a data analytics workflow, starting with data exploration and preparation, followed by SQL-based analysis and interactive dashboard development in Power BI.

## Project Objectives

- Explore and understand customer shopping data.
- Perform data inspection and preparation using Python and Pandas.
- Store and manage data using PostgreSQL.
- Perform analytical queries using SQL.
- Identify purchasing patterns across different customer segments.
- Develop an interactive Power BI dashboard to visualise key findings.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and preparation |
| Pandas | Data manipulation and exploration |
| NumPy | Numerical computing |
| Jupyter Notebook | Interactive Python environment |
| PostgreSQL | Relational database management |
| SQL | Data querying and analysis |
| SQLAlchemy | Database connectivity |
| psycopg2 | PostgreSQL connectivity |
| Microsoft Power BI | Interactive dashboard development |

## Project Workflow

### 1. Data Exploration and Preparation

- Loaded the dataset using Pandas.
- Inspected records using `df.head()`.
- Examined descriptive statistics using `df.describe(include='all')`.
- Created an `age_group` column for demographic analysis.

### 2. Database Management

- Established a connection between Python and PostgreSQL.
- Used SQLAlchemy and psycopg2 for database connectivity.
- Loaded the customer dataset into a PostgreSQL table named `customer`.

### 3. SQL-Based Analysis

Performed analytical queries to investigate:

- Revenue distribution by gender.
- Top five products by average purchase amount.
- Average purchase amount by shipping type.
- Customer subscription patterns.
- Product category performance.
- Customer purchasing behaviour.

### 4. Power BI Dashboard

Developed an interactive dashboard titled **Customer Behaviour Dashboard**, featuring:

- Total number of customers.
- Average purchase amount.
- Average review rating.
- Customer distribution by subscription status.
- Revenue and sales by product category.
- Revenue and sales by age group.
- Interactive slicers for subscription status, gender, category and shipping type.

## Key Findings

Based on the available SQL query outputs and dashboard:

- Total dataset records: **3,900**.
- Average purchase amount: approximately **$59.76**.
- Average review rating: approximately **3.75**.
- Clothing is the most frequent product category, with 1,737 records.
- Express shipping has a higher average purchase amount than Standard shipping in the analysed output.
- T-shirt has the highest displayed average purchase amount among the five products in the supplied SQL result.

## Repository Structure

```text
Customer_Behaviour_Analysis/
│
├── README.md
├── Customer_Analysis.ipynb
├── SQL_Queries.sql
├── Customer_Analysis.pbix
├── Project_Report.docx
├── Project_Presentation.pptx
│
└── dataset/
    └── customer_shopping_behavior.csv
```

*The repository structure may be adjusted according to the files uploaded. The dataset should only be
