# customer_behaviour_analysis
Built an end-to-end retail analytics solution using Python, SQL, PostgreSQL, and Power BI to analyze customer purchasing behavior, identify revenue-driving segments, evaluate product performance, and deliver data-driven business recommendations through interactive dashboards.
# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using Python, SQL, and Power BI to uncover actionable business insights. The workflow covers the complete data analytics lifecycle, including data loading, exploratory data analysis (EDA), data cleaning, SQL-based business analysis, dashboard development, report generation, and presentation creation.

The objective is to understand customer purchasing patterns, identify key revenue drivers, and provide data-driven recommendations for business growth.

---

## Dataset

The dataset contains customer shopping transactions, demographic information, purchase details, and customer behavior metrics.

**Key Features:**

* Customer Demographics (Age, Gender, Location)
* Purchase Information (Product, Category, Amount, Season)
* Customer Behavior (Subscription Status, Purchase Frequency)
* Discounts and Promotions
* Product Ratings and Reviews
* Shipping Preferences

---

## Tools & Technologies

| Tool                                        | Purpose                           |
| ------------------------------------------- | --------------------------------- |
| Python (Pandas, NumPy, Matplotlib, Seaborn) | Data Cleaning & EDA               |
| SQL (PostgreSQL / MySQL / SQL Server)       | Data Analysis & Business Queries  |
| Power BI                                    | Interactive Dashboard Development |
| Gamma                                       | Presentation Creation             |
| Jupyter Notebook                            | Data Analysis Workflow            |

---

## Project Workflow

### 1. Data Loading

* Imported dataset using Python.
* Examined dataset structure and data types.
* Performed initial data quality assessment.

### 2. Exploratory Data Analysis (EDA)

* Analyzed customer demographics.
* Studied spending patterns and purchasing behavior.
* Identified trends, correlations, and outliers.
* Generated visualizations to support insights.

### 3. Data Cleaning

* Handled missing values.
* Standardized column names and formats.
* Removed inconsistencies and duplicates.
* Created additional features for analysis.

### 4. SQL Analysis

Performed business-focused analysis using SQL:

* Revenue analysis by customer segments.
* Customer spending behavior.
* Product performance evaluation.
* Subscription impact analysis.
* Customer loyalty and retention analysis.
* Purchase frequency and trend analysis.

### 5. Dashboard Development

Created an interactive Power BI dashboard featuring:

* Revenue KPIs
* Customer Segmentation
* Product Performance Analysis
* Subscription Insights
* Purchase Trends
* Interactive Filters and Slicers

### 6. Reporting & Presentation

* Prepared a business insights report.
* Created a presentation using Gamma.
* Summarized findings and recommendations for stakeholders.

---

## Dashboard Highlights

* Total Revenue Overview
* Customer Demographics Analysis
* Best-Selling Products
* Subscription vs Non-Subscription Comparison
* Age Group Revenue Distribution
* Customer Loyalty Insights
* Purchase Behavior Trends

---

## Key Results

* Identified high-value customer segments.
* Discovered top-performing products and categories.
* Evaluated the impact of discounts and promotions.
* Analyzed subscription behavior and customer retention.
* Generated recommendations to improve revenue and customer engagement.

---

## Business Recommendations

* Enhance customer loyalty programs.
* Promote subscription benefits to increase retention.
* Optimize discount strategies for profitability.
* Focus marketing efforts on high-value customer segments.
* Improve visibility of top-rated products.

---

## Repository Structure

```text
├── data/
│   └── raw_dataset.csv
├── notebooks/
│   └── eda_analysis.ipynb
├── sql/
│   └── business_queries.sql
├── dashboard/
│   └── powerbi_dashboard.pbix
├── reports/
│   └── project_report.pdf
├── presentation/
│   └── gamma_presentation.pdf
├── README.md
```

---

## How to Run

### Python Analysis

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy
jupyter notebook
```

Open the notebook and run all cells sequentially.

### SQL Analysis

1. Create a database in PostgreSQL, MySQL, or SQL Server.
2. Import the cleaned dataset.
3. Execute queries from the `sql/` folder.

### Power BI Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh the dataset connection.
3. Explore the interactive dashboard.

---

## Author

**Radhika Vishwakarma**
Aspiring Data Analyst | SQL | Python | Power BI | Data Visualization

---

*This project demonstrates end-to-end data analytics skills including data preparation, SQL analysis, dashboard development, business reporting, and stakeholder presentation.*
