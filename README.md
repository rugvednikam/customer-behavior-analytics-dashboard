# Customer Behavior Analytics Dashboard

## Overview

This project is an end-to-end customer behavior analytics solution built using Python, PostgreSQL, SQL, and Power BI. The objective of this project is to analyze customer purchasing behavior, subscription trends, review ratings, and category-wise revenue performance to generate actionable business insights.

The project demonstrates a complete analytics workflow including:

* Data Cleaning and Preprocessing
* ETL Pipeline Development
* PostgreSQL Database Integration
* SQL-Based Data Analysis
* Interactive Dashboard Creation in Power BI

---

# Tech Stack

* **Python** (Pandas, SQLAlchemy)
* **PostgreSQL**
* **SQL**
* **Power BI**
* **Power Query**
* **DAX**

---

# Project Workflow

## 1. Data Collection

Customer transaction and purchasing behavior dataset collected in CSV format.

## 2. Data Cleaning & Preprocessing

Performed data cleaning using Python:

* Removed null values
* Handled duplicates
* Standardized categorical values
* Converted data types
* Prepared dataset for analysis

## 3. ETL Pipeline

Built an ETL pipeline using Python and SQLAlchemy:

* Extracted data from CSV
* Transformed cleaned data
* Loaded data into PostgreSQL database

## 4. SQL Analysis

Executed SQL queries to analyze:

* Revenue trends
* Customer segmentation
* Category performance
* Subscription behavior
* Purchase distribution

## 5. Power BI Dashboard

Created an interactive dashboard with:

* KPI Cards
* Donut Charts
* Revenue Analysis
* Customer Segmentation
* Dynamic Filters and Slicers
* Age Group Analysis
* Category-Wise Insights

---

# Dashboard Features

* Total Revenue Tracking
* Customer Count Analysis
* Average Purchase Amount
* Subscription Status Distribution
* Revenue by Product Category
* Age Group Segmentation
* Shipping Type Analysis
* Gender-Based Insights

---

# Key Insights

* Clothing category generated the highest revenue contribution.
* Non-subscribed customers represented the majority of purchases.
* Young adult customer groups showed higher purchasing activity.
* Revenue trends varied significantly across product categories.

---

# Project Structure

```bash
customer-behavior-analytics-dashboard/
│
├── dataset/
│   └── customer_data.csv
│
├── python/
│   └── etl_pipeline.py
│
├── sql/
│   └── customer_queries.sql
│
├── dashboard/
│   └── Customer_Behavior_Dashboard.pbix
│
├── screenshots/
│   └── dashboard_overview.png
│
├── README.md
└── requirements.txt
```

# Installation & Setup

## Clone Repository

```bash
git clone https://github.com/yourusername/customer-behavior-analytics-dashboard.git
```

## Install Dependencies

```bash
pip install pandas sqlalchemy psycopg2
```

## Configure PostgreSQL Connection

Update database credentials inside:

```python
etl_pipeline.py
```

Example:

```python
username = 'postgres'
password = 'your_password'
host = 'localhost'
port = '5432'
database = 'customer_behavior'
```

## Run ETL Pipeline

```bash
python etl_pipeline.py
```

## Open Power BI Dashboard

Open:

```text
Customer_Behavior_Dashboard.pbix
```

---

# Future Improvements

* Deploy dashboard to Power BI Service
* Add predictive analytics models
* Integrate real-time data streaming
* Implement advanced customer segmentation

---

# Author

Rugved Nikam

* LinkedIn: https://linkedin.com/in/rugvednikam
* GitHub: https://github.com/rugvednikam
