# Customer Shopping Behavior Analysis

**An End-to-End Data Analytics Project Using Python, PostgreSQL & Power BI**

## Overview

This project explores customer shopping behavior using data analytics techniques to identify purchasing patterns, understand customer segments, evaluate product performance, and generate actionable business insights.

The project follows an end-to-end analytics workflow, starting with data preparation and exploratory data analysis (EDA) in Python, followed by SQL-based business analysis using PostgreSQL and interactive dashboard development using Power BI.

The objective is to transform raw customer shopping data into meaningful insights that can support business decision-making, customer retention strategies, and sales optimization.

## Business Problem

Retail businesses need to understand their customers to improve sales performance, customer satisfaction, and retention.

This project addresses key business questions:

- Which customer segments contribute the most revenue?
- What are the purchasing patterns across different age groups?
- Do subscribed customers spend more than non-subscribers?
- How do discounts influence purchasing behavior?
- Which products receive the highest customer ratings?
- Which products perform best within each category?
- Are repeat customers more likely to subscribe?
- How do shipping preferences relate to purchase amounts?

## Dataset

The project uses a customer shopping behavior dataset containing **3,900 records and 19 columns**.

The dataset includes information about:

| Category | Attributes |
|---|---|
| Customer Demographics | Customer ID, Age, Gender, Location |
| Purchase Information | Item Purchased, Category, Purchase Amount |
| Product Details | Size, Color, Season, Review Rating |
| Customer Engagement | Subscription Status, Previous Purchases |
| Transaction Details | Payment Method, Shipping Type |
| Purchase Behavior | Discount Applied, Frequency of Purchases |

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data preparation and exploratory analysis |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Data visualization |
| PostgreSQL | Database management and querying |
| SQL | Business analysis and data extraction |
| SQLAlchemy | Python-to-PostgreSQL connectivity |
| Power BI | Interactive dashboard development |
| Jupyter Notebook | Python development environment |

## Project Workflow

### 1. Data Loading & Preparation – Python

The dataset is loaded into Python using Pandas.

Key activities include:
- Importing and inspecting the dataset.
- Understanding data types and column structures.
- Identifying missing values and data quality issues.
- Preparing data for further analysis.
- Creating derived customer attributes where applicable.

### 2. Exploratory Data Analysis (EDA)

EDA helps understand the underlying patterns and characteristics of customer shopping behavior.

The analysis focuses on:
- Customer demographics.
- Product and category distribution.
- Purchase amount distribution.
- Customer purchase frequency.
- Discount and subscription behavior.
- Customer ratings and preferences.

### 3. SQL Analysis – PostgreSQL

The prepared dataset is stored in PostgreSQL for structured querying and business analysis.

SQL concepts applied include:

- SELECT and WHERE
- GROUP BY and ORDER BY
- Aggregate Functions
- Subqueries
- CASE WHEN
- Common Table Expressions (CTEs)
- Window Functions
- ROW_NUMBER()

Ten business questions are explored through SQL queries to identify customer trends, product performance, revenue contributions, and purchasing patterns.

### 4. Power BI Dashboard

Power BI is used to present customer shopping insights through interactive visualizations.

The dashboard is designed to help users explore customer behavior, purchasing trends, and sales performance.

**Dashboard Preview**

<!-- Add your Power BI dashboard screenshot here -->
<!-- Example: ![Customer Behavior Dashboard](images/customer_behavior_dashboard.png) -->

Power BI file: `customer_behavior_dashboard.pbix`

### 5. Reporting & Presentation

The analysis is supported by a project report, business problem document, and presentation summarizing the project and its analytical approach.

## Key Analytical Areas

| Analytical Area | Business Objective |
|---|---|
| Customer Segmentation | Understand customer loyalty and repeat purchases |
| Revenue Analysis | Compare revenue across customer groups |
| Product Performance | Identify highly rated and frequently purchased products |
| Discount Analysis | Understand product-level discount usage |
| Subscription Analysis | Evaluate subscriber purchasing behavior |
| Age Group Analysis | Compare revenue contributions across age segments |
| Shipping Analysis | Compare purchasing patterns by shipping preference |

## Business Recommendations

The analysis can support business decisions such as:

1. Developing targeted marketing campaigns for different customer segments.
2. Improving customer retention through subscription and loyalty strategies.
3. Optimizing promotional campaigns based on product-level discount patterns.
4. Identifying high-performing products for inventory planning.
5. Understanding customer preferences to improve product and service offerings.

*Specific recommendations should be finalized based on the actual SQL results and Power BI dashboard findings.*

## Repository Structure

```text
customer_behavior_analysis/
│
├── customer_shopping_behavior.csv
│
├── cleaning_customer_behavior_data.ipynb
│
├── Customer-Shopping-Behavior-Analysis.sql
│
├── customer_behavior_dashboard.pbix
│
├── Business Problem Document.pdf
│
├── Customer Shopping Behavior Analysis.pdf
│
├── Customer-Shopping-Behavior-Analysis.pptx
│
├── LICENSE
│
└── README.md
```

## How to Run the Project

### Prerequisites

Install the following:

- Python 3.x
- Jupyter Notebook
- PostgreSQL
- pgAdmin 4
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone https://github.com/masoodsaid123/customer_behavior_analysis.git

cd customer_behavior_analysis
```

### Step 2: Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary jupyter
```

### Step 3: Load and Prepare the Dataset

Open the Jupyter Notebook:

```bash
jupyter notebook cleaning_customer_behavior_data.ipynb
```

Run the notebook cells to prepare the dataset and configure the PostgreSQL connection.

### Step 4: Configure PostgreSQL

1. Create a database in PostgreSQL.
2. Configure the connection details in the Python notebook using environment variables.
3. Upload the prepared dataset into a PostgreSQL table.
4. Ensure the SQL queries reference the correct table name.

### Step 5: Execute SQL Queries

Open the SQL file in pgAdmin or another PostgreSQL client.

Execute the queries to explore the business questions and retrieve analytical insights.

### Step 6: Open the Power BI Dashboard

Open:

`customer_behavior_dashboard.pbix`

Refresh the data connection if necessary to explore the dashboard.

## Results

This project demonstrates an end-to-end data analytics workflow involving:

- Data preparation and exploration using Python.
- Relational database management using PostgreSQL.
- Business analysis using SQL.
- Interactive data visualization using Power BI.
- Translating analytical questions into business recommendations.

## Author

**Masood Said**

Data Analytics | Python | SQL | PostgreSQL | Power BI

GitHub: https://github.com/masoodsaid123

---

## License

This project is available under the MIT License. See the `LICENSE` file for details.
