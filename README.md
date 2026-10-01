# Customer Behavior Analytics

An end-to-end customer behavior analytics project using Python, Pandas, PostgreSQL, SQL, and Power BI.

## 📌 Project Overview

This project analyzes customer shopping behavior using an end-to-end data analytics workflow, starting from raw customer data and progressing through data cleaning, database storage, SQL analysis, and interactive Power BI visualization.

The project workflow is:

**Raw Data → Python/Pandas → PostgreSQL → SQL Analysis → Power BI Dashboard**

The dataset contains 3,900 customer records with information related to customer demographics, purchases, products, categories, payment methods, discounts, subscriptions, and purchase frequency.

## 🎯 Project Objectives

- Clean and prepare raw customer shopping data
- Perform data analysis using Python and Pandas
- Transform the dataset for analytical use
- Store the cleaned data in PostgreSQL
- Perform business-oriented analysis using SQL
- Build an interactive Power BI dashboard
- Visualize customer purchasing behavior and patterns
- Understand an end-to-end data analytics workflow

## 🛠️ Technologies Used

### Programming & Data Analysis
- Python
- Pandas
- Jupyter Notebook

### Database
- PostgreSQL
- pgAdmin

### Query Language
- SQL

### Visualization & Business Intelligence
- Microsoft Power BI

### Development Tools
- Visual Studio Code
- Git
- GitHub

## 🔄 Project Workflow

### 1. Data Loading

The customer shopping dataset was loaded into Python using Pandas.

The dataset was inspected to understand its structure, columns, data types, and available customer and purchase information.

### 2. Data Cleaning & Transformation

Python and Pandas were used to prepare the dataset for analysis.

The process included:

- Inspecting the dataset
- Checking data types
- Cleaning and transforming relevant fields
- Preparing categorical and numerical data
- Creating analytical fields
- Transforming purchase frequency information into numerical values

### 3. PostgreSQL Database

The processed dataset was loaded into PostgreSQL for structured storage and analysis.

**Database:** `customer_behavior`

**Table:** `customer`

### 4. SQL Analysis

SQL was used to analyze customer behavior and answer business-oriented questions.

The analysis included areas such as:

- Customer demographics
- Revenue
- Purchase behavior
- Product categories
- Purchase frequency
- Payment methods
- Discounts and promotions
- Subscription behavior

The SQL queries are available in:

`sql/customer_behavior_analysis.sql`

### 5. Power BI Dashboard

The PostgreSQL data was connected to Power BI to create an interactive dashboard.

The dashboard provides visual analysis of customer behavior and purchasing patterns using charts, KPIs, filters, and other visualizations.

Power BI report:

`powerbi/customer_behavior_dashboard.pbix`

## 📊 Dashboard Preview

![Customer Behavior Dashboard](screenshots/dashboard.png)

## 📁 Project Structure

```text
customer-behaviour/
│
├── python/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
├── customer_shopping_behavior.csv
│
└── README.md

🧠 Skills Demonstrated

Python

Pandas

Data Cleaning

Data Transformation

Exploratory Data Analysis

PostgreSQL

SQL

Database Management

Business Data Analysis

Data Visualization

Power BI

Dashboard Development

End-to-End Data Analytics


📚 Key Learning Outcomes

This project provided practical experience in building an end-to-end analytics workflow:

Data → Python → Database → SQL → Power BI

It helped develop an understanding of how raw data can be cleaned, stored, analyzed, and transformed into interactive business dashboards.

🚀 Future Improvements

Add more advanced Power BI measures using DAX

Create additional dashboard pages

Perform deeper customer segmentation

Add more advanced statistical analysis

Automate the data pipeline

Implement automated database refresh workflows

Extend the project into a real-time analytics workflow


👤 Author

Shivasai Reddy

Computer Science Engineering | AI/ML

Interests

Artificial Intelligence

Machine Learning

Python

Data Analytics

Software Development


⭐ Project Purpose

This project was developed as a practical portfolio project to gain hands-on experience with data analytics, SQL, databases, and business intelligence tools while building an end-to-end data workflow.
