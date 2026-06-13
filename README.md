# Customer Shopping Behavior Analysis

## Overview

This Data Analytics project focuses on analyzing customer shopping behavior to uncover valuable business insights. The project involves data collection, cleaning, exploratory data analysis (EDA), SQL-based business analysis, and dashboard development.

The workflow integrates Python, PostgreSQL, and Power BI to transform raw customer transaction data into actionable insights that can support business decision-making.

---

## Dataset

**Dataset Name:** Customer Shopping Behavior Dataset

**Source:** Kaggle

The dataset contains customer transaction records, including:

* Customer demographics
* Purchase details
* Product categories
* Subscription status
* Shipping preferences
* Discount usage
* Customer ratings
* Purchase frequency

---

## Tools & Technologies

### Programming Languages

* Python
* SQL

### Python Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQLAlchemy
* Psycopg2

### Database

* Neon PostgreSQL

### Visualization

* Power BI

### Documentation & Presentation

* Microsoft Word (Project Report)
* Gamma AI (Presentation/PPT)

---

## Project Workflow

### 1. Data Collection

* Downloaded the dataset from Kaggle.
* Imported the CSV file into Google Colab.

### 2. Data Cleaning

* Checked dataset structure and data types.
* Handled missing values.
* Renamed columns for consistency.
* Removed redundant fields.
* Performed data validation and preprocessing.

### 3. Exploratory Data Analysis (EDA)

* Analyzed customer demographics.
* Explored purchasing patterns.
* Identified spending trends.
* Evaluated subscription behavior.
* Generated visualizations and summary statistics.

### 4. Database Integration

* Connected Google Colab to Neon PostgreSQL.
* Loaded the cleaned dataset into PostgreSQL tables using SQLAlchemy.
* Stored data for SQL-based business analysis.

### 5. SQL Analysis

Business queries were performed to analyze:

* Revenue by gender
* Customer segmentation
* Subscriber vs non-subscriber behavior
* Product performance
* Discount effectiveness
* Revenue by age groups
* Shipping preferences
* Top-rated products

### 6. Dashboard Development

* Connected Power BI directly to Neon PostgreSQL.
* Imported required tables.
* Built interactive dashboards and reports.

### 7. Documentation & Presentation

* Created a detailed project report.
* Designed a presentation using Gamma AI.
* Summarized findings and recommendations.

---

## Dashboard Features

The Power BI dashboard includes:

* Revenue Analysis
* Customer Demographics
* Product Category Performance
* Customer Segmentation
* Subscription Insights
* Shipping Analysis
* Top Products Overview

---

## Key Results

* Identified high-value customer segments.
* Analyzed revenue contribution across demographics.
* Evaluated the impact of discounts on purchasing behavior.
* Compared subscriber and non-subscriber spending patterns.
* Identified top-performing products and categories.
* Generated actionable business recommendations.

---

## Business Recommendations

* Promote subscription-based programs.
* Reward loyal customers through retention strategies.
* Optimize discount campaigns.
* Focus marketing efforts on high-revenue customer groups.
* Improve visibility of top-rated products.

---

## How to Run the Project

### Step 1: Clone the Repository

```bash
git clone <repository-link>
cd customer-shopping-behavior-analysis
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary
```

### Step 3: Load Dataset

Upload the CSV dataset into Google Colab or your local Python environment.

### Step 4: Run Data Cleaning & EDA

Execute the Python notebook to:

* Clean data
* Perform EDA
* Generate visualizations

### Step 5: Connect to PostgreSQL

Configure database credentials and load the processed dataset into PostgreSQL.

### Step 6: Execute SQL Queries

Run the SQL scripts to generate business insights and analytical reports.

### Step 7: Open Power BI Dashboard

Connect Power BI to PostgreSQL and refresh the dashboard to visualize insights.

---

## Project Architecture

```text
Kaggle Dataset
      │
      ▼
Google Colab
(Python + Pandas)
      │
      ▼
Data Cleaning & EDA
      │
      ▼
Neon PostgreSQL
      │
      ▼
SQL Analysis
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Insights
```

---

## Author

**Dushyant Pachauri**

Data Analytics Project using Python, SQL, PostgreSQL, and Power BI.

