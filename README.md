# DecodeLabs Data Analytics Internship

## Student Information

**Name:** GADDAM SAI SANDESH

**Domain:** Data Analytics

**Batch:** 2026

---

# Project 1 – Data Cleaning and Preparation

## Objective

The objective of this project was to clean a raw dataset by identifying missing values, removing duplicate records, and correcting inconsistent data formats. Data cleaning is an important step because it improves the quality and reliability of data before performing any analysis.

## Tasks Performed

* Identified missing values in the dataset.
* Handled null values appropriately.
* Checked for duplicate records.
* Verified that duplicate Order IDs were not present.
* Standardized date formats.
* Verified data consistency and integrity.
* Generated validation and audit reports.

## Key Outcome

A cleaned and validated dataset was prepared for further analysis.

## Skills Used

* Data Cleaning
* Data Validation
* Data Preparation
* Microsoft Excel
* Data Quality Assessment

---

# Project 2 – Exploratory Data Analysis (EDA)

## Objective

The objective of this project was to analyze the cleaned dataset and discover meaningful patterns, trends, and business insights through descriptive statistics and exploratory analysis.

## Tasks Performed

* Calculated basic statistical measures such as:

  * Mean
  * Median
  * Count
  * Minimum
  * Maximum

* Conducted trend analysis.

* Identified outliers using statistical techniques.

* Performed correlation analysis.

* Generated summary reports and dashboards.

* Created visualizations for better understanding of the data.

## Key Findings

* Product sales trends were identified.
* Revenue contribution of products was analyzed.
* Customer purchasing patterns were observed.
* Payment method usage was evaluated.
* Outliers and unusual transactions were detected.

## Skills Used

* Exploratory Data Analysis
* Descriptive Statistics
* Dashboard Development
* Data Visualization
* Business Insight Generation
* Microsoft Excel

---

# Project 3 – SQL Data Analysis

## Objective

The objective of this project was to perform SQL-based data analysis by importing the dataset into MySQL and executing queries to extract meaningful business insights.

## Environment Used

* MySQL 8.0
* Command Line Client
* CSV Dataset

## Tasks Performed

### Database Operations

* Created a database.
* Created tables.
* Imported the dataset into MySQL.
* Verified successful data loading.

### SQL Concepts Implemented

#### SELECT

Used to retrieve records from the dataset.

#### WHERE

Used to filter records based on specific conditions.

#### ORDER BY

Used to sort records based on sales values.

#### GROUP BY

Used to group records and perform category-wise analysis.

#### COUNT()

Used to calculate the total number of records.

#### SUM()

Used to calculate total revenue.

#### AVG()

Used to calculate average order value.

## Sample Queries Executed

```sql
SELECT * FROM sales;
```

```sql
SELECT COUNT(*) FROM sales;
```

```sql
SELECT Product, COUNT(*)
FROM sales
GROUP BY Product;
```

```sql
SELECT Product, SUM(TotalPrice)
FROM sales
GROUP BY Product;
```

```sql
SELECT AVG(TotalPrice)
FROM sales;
```

```sql
SELECT *
FROM sales
WHERE TotalPrice > 1000;
```

```sql
SELECT *
FROM sales
ORDER BY TotalPrice DESC;
```

## Key Findings

* Successfully imported 1200 records into MySQL.
* Product performance was analyzed.
* Revenue trends were identified.
* Payment method distribution was analyzed.
* Order status distribution was evaluated.

## Skills Used

* SQL Fundamentals
* MySQL
* Data Querying
* Data Aggregation
* Business Intelligence
* Database Management

---

# Overall Learning Outcomes

Through these three projects, I gained practical experience in:

* Data Cleaning and Preparation
* Exploratory Data Analysis
* Data Visualization
* SQL Querying
* Database Management
* Business Insight Generation
* Analytical Thinking
* Problem Solving

These projects helped strengthen my understanding of the complete data analytics workflow, starting from raw data preparation to statistical analysis and SQL-based business intelligence extraction.

---

## Conclusion

The completion of these three projects provided hands-on exposure to real-world data analytics processes. The projects demonstrated the ability to clean, analyze, and extract meaningful insights from data using both Excel and SQL. The knowledge gained through these tasks forms a strong foundation for advanced analytics, dashboard development, and data-driven decision making.
