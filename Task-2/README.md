# 📊 CODSOFT Internship — Task 2: Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project is part of my **Data Analytics Internship at CODSOFT**.

The objective of this task is to perform **Exploratory Data Analysis (EDA)** on a Restaurant Sales dataset using Python and Pandas.

The analysis focuses on understanding the dataset, descriptive statistics, trends, distributions, relationships between variables, outliers, unusual patterns, and key business insights.

---

## 🎯 Objectives

The main objectives of this EDA project are:

- Load and examine the dataset.
- Understand the structure and features of the data.
- Perform descriptive statistical analysis.
- Identify trends and patterns.
- Analyze distributions of numerical variables.
- Identify relationships between variables.
- Detect outliers and unusual patterns.
- Use summary statistics to answer business questions.
- Prepare a short report highlighting the findings.

---

## 🗂️ Dataset Information

The Restaurant Sales dataset contains information about orders, customers, products, prices, quantities, order totals, order dates, and payment methods.

### Dataset Columns

| Column | Description |
|---|---|
| `order_id` | Unique order identifier |
| `customer_id` | Unique customer identifier |
| `category` | Product category |
| `item` | Product/item name |
| `price` | Product price |
| `quantity` | Quantity purchased |
| `order_total` | Total value of the order |
| `order_date` | Date of the order |
| `payment_method` | Payment method used |

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 🔍 EDA Process

### 1. Dataset Loading

The cleaned Restaurant Sales dataset was loaded using Pandas.

```python
import pandas as pd
import numpy as np

data = pd.read_csv("../data/processed/restaurant_sales_data_cleaned.csv")
```

### 2. Dataset Examination

The dataset was examined using:

- `head()`
- `shape`
- `columns`
- `dtypes`
- `info()`

This helped understand the number of records, columns, data types, and overall structure.

### 3. Descriptive Statistics

Descriptive statistics were used to understand numerical features such as:

- `price`
- `quantity`
- `order_total`

The following statistical measures were examined:

- Mean
- Median
- Standard deviation
- Minimum
- Maximum
- Quartiles

### 4. Missing Values

Missing values were checked using Pandas to ensure the dataset was suitable for analysis.

### 5. Duplicate Records

Duplicate records were identified to verify the quality and consistency of the dataset.

### 6. Trend Analysis

Different group-based analyses were performed to identify important sales trends, including:

- Category-wise sales
- Product-wise sales
- Payment method usage
- Quantity sold

### 7. Distribution Analysis

The distribution of numerical variables was examined to understand the spread and behavior of:

- Price
- Quantity
- Order Total

### 8. Relationship Analysis

Relationships between numerical variables were examined using correlation analysis.

Important relationships included:

- Quantity vs Order Total
- Price vs Order Total

### 9. Outlier Detection

The **Interquartile Range (IQR)** method was used to identify potential outliers in the `order_total` column.

The following values were calculated:

- Q1
- Q3
- IQR
- Lower Bound
- Upper Bound

Values outside the calculated range were considered potential outliers.

---

## 💡 Key Business Questions

The EDA was used to answer the following questions:

1. What is the total sales generated?
2. What is the average order value?
3. Which category has the highest sales?
4. Which category has the lowest sales?
5. Which product has the highest sales?
6. Which payment method is used most frequently?
7. What is the relationship between quantity and order total?
8. How many sales outliers are present?

---

## 📊 Business Insights

The analysis provides insights into:

- Overall restaurant sales performance.
- Average order value.
- Best and lowest-performing categories.
- Top-performing products.
- Customer payment preferences.
- Relationship between quantity and sales.
- Unusual or extreme sales transactions.

---

## 📝 Short Report

A short EDA report is included in the `reports/` folder.

The report summarizes the dataset, descriptive statistics, sales trends, relationships, outlier analysis, and key business findings.

---

## 📁 Project Structure

```text
Task-2-EDA/
│
├── data/
│   ├── raw/
│   │   └── restaurant_sales_data.csv
│   │
│   └── processed/
│       └── restaurant_sales_data_cleaned.csv
│
├── notebooks/
│   └── Task-2-EDA.ipynb
│
│
└── README.md
```

---

## 🚀 Key Learning Outcomes

Through this project, I gained practical experience in:

- Exploratory Data Analysis
- Des
