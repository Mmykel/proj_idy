# Nigerian Retail Sales Analysis Project

## Overview

This project analyzes a Nigerian retail sales dataset to uncover business insights through data cleaning, transformation, exploratory data analysis (EDA), KPI reporting, and visualization.

The notebook demonstrates a complete data analytics workflow, from raw data preparation to generating actionable business insights for decision-making.

## Objectives

* Clean and prepare retail sales data
* Handle missing values and duplicates
* Standardize categorical variables
* Create derived business metrics
* Calculate key performance indicators (KPIs)
* Analyze sales trends over time
* Identify top-performing products
* Identify high-revenue customer locations
* Visualize business performance metrics

---

## Dataset Features

The dataset contains retail transaction records with fields such as:

* Order Date
* Product Category
* Product
* Customer Location
* Quantity Sold
* Unit Price (NGN)

Additional fields created during analysis:

* Year
* Month Name
* Quarter
* Year-Month
* Total Sales

---

## Data Cleaning Process

The following cleaning operations were performed:

### 1. Date Conversion

Converted the `Order Date` column into a proper datetime format for time-series analysis.

### 2. Missing Value Treatment

Missing product prices were filled using forward-fill and backward-fill techniques grouped by product.

### 3. Duplicate Removal

Duplicate records were identified and removed to improve data quality.

### 4. Text Standardization

Categorical columns were cleaned by:

* Removing extra spaces
* Standardizing capitalization
* Improving consistency across records

---

## Feature Engineering

New analytical features were created:

| Feature     | Description                |
| ----------- | -------------------------- |
| Year        | Sales year                 |
| Month Name  | Sales month                |
| Quarter     | Business quarter           |
| Year-Month  | Monthly aggregation period |
| Total Sales | Unit Price × Quantity Sold |

---

## Key Performance Indicators (KPIs)

The project calculates:

### Total Revenue

Overall sales generated across all transactions.

### Average Order Value (AOV)

Average revenue generated per order.

### Average Unit Price

Average selling price of products.

### Total Quantity Sold

Total units sold across all products.

### Month-over-Month Growth

Percentage change in sales compared to the previous month.

---

## Business Questions Answered

### Sales Performance

* How much revenue was generated?
* What are the monthly sales trends?
* Which months recorded the highest sales?

### Product Analysis

* Which products generate the most revenue?
* What are the top-performing products?

### Geographic Analysis

* Which customer locations contribute the most sales?
* What are the top 5 revenue-generating locations?

### Time-Based Analysis

* How does sales performance vary by year?
* What quarterly trends can be observed?

---

## Visualizations

The notebook includes visualizations such as:

### Monthly Sales Trend

Line charts showing revenue progression over time.

### Top Products Analysis

Revenue contribution by product.

### Customer Location Performance

Comparison of sales across locations.

### KPI Dashboard

A business intelligence-style dashboard highlighting key metrics.

---

## Technologies Used

### Python Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Analytics Techniques

* Data Cleaning
* Data Transformation
* Feature Engineering
* Exploratory Data Analysis (EDA)
* KPI Reporting
* Business Intelligence Visualization

---

## Project Structure

```text
├── pyprop.ipynb
├── nigerian_retail_sales_data.csv
├── README.md
```

---

## How to Run

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/nigerian-retail-sales-analysis.git
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run the Notebook

Open:

```text
pyprop.ipynb
```

and execute all cells.

---

## Sample Insights

The analysis can help businesses:

* Track sales performance over time
* Identify high-value products
* Discover top-performing markets
* Monitor growth trends
* Improve inventory planning
* Support data-driven decision making

---

## Future Improvements

* Interactive Power BI Dashboard
* Streamlit Web Application
* Customer Segmentation Analysis
* Sales Forecasting with Machine Learning
* Product Recommendation System
* Automated Reporting Pipeline

---

## Author

Data Analytics Project focused on retail business intelligence and sales performance analysis using Python.
