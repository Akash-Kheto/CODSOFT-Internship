# 📊 CODSOFT Internship — Task 2: Exploratory Data Analysis (EDA)

<p align="center">

<img src="https://img.shields.io/badge/CODSOFT-Internship-blue?style=for-the-badge" alt="CODSOFT Internship"/>
<img src="https://img.shields.io/badge/Task-02-orange?style=for-the-badge" alt="Task 2"/>
<img src="https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python" alt="Python"/>
<img src="https://img.shields.io/badge/Pandas-EDA-purple?style=for-the-badge&logo=pandas" alt="Pandas"/>
<img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" alt="Jupyter"/>

</p>

---

## 📌 Project Overview

This project is part of my **Data Analytics Internship at CODSOFT**.

The objective of this task is to perform **Exploratory Data Analysis (EDA)** on a **Restaurant Sales Dataset** using Python, Pandas, and NumPy.

The analysis focuses on understanding the dataset, descriptive statistics, trends, distributions, relationships between variables, outliers, unusual patterns, and key business insights.

---

## 🎯 Objectives

The main objectives of this EDA project are:

- 📥 Load and examine the dataset
- 🔎 Understand the structure and features of the data
- 📊 Perform descriptive statistical analysis
- 📈 Identify trends and patterns
- 📉 Analyze distributions of numerical variables
- 🔗 Identify relationships between variables
- 🚨 Detect outliers and unusual patterns
- 💡 Answer important business questions
- 📝 Prepare a short EDA report

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

<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>

</p>

---

## 🔄 EDA Workflow

```text
                    ┌─────────────────────┐
                    │   Cleaned Dataset   │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │ Dataset Examination │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │ Descriptive Stats   │
                    └──────────┬──────────┘
                               ↓
              ┌────────────────┴────────────────┐
              ↓                                 ↓
     ┌──────────────────┐             ┌──────────────────┐
     │ Trend Analysis   │             │ Distribution     │
     └────────┬─────────┘             └────────┬─────────┘
              ↓                                ↓
     ┌──────────────────┐             ┌──────────────────┐
     │ Relationship     │             │ Outlier Detection│
     │ Analysis         │             │                  │
     └────────┬─────────┘             └────────
