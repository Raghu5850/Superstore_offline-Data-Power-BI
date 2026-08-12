# Superstore Offline Data Analysis – Power BI

## 📊 Project Overview

This project is a **Power BI data analysis and business intelligence project** based on Superstore offline sales data.

The objective of this project is to transform raw sales data into meaningful business insights using **Power BI, Power Query, data modeling, DAX, and interactive dashboards**.

The dashboard helps analyze sales performance, profitability, customers, products, categories, regions, and trends to support data-driven business decisions.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze overall sales and profit performance
* Identify the most profitable and loss-making products
* Analyze sales by category and sub-category
* Understand regional and state-wise performance
* Analyze customer purchasing behavior
* Identify top-performing customers
* Analyze monthly and yearly sales trends
* Track key business KPIs
* Create an interactive Power BI dashboard
* Generate actionable business insights

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Microsoft Excel / CSV**
* **Data Cleaning & Transformation**
* **Interactive Data Visualization**

---

## 📂 Project Files

### Power BI Report

 [Superstore_Offline_Data.pbix](https://github.com/Raghu5850/Superstore_offline-Data-Power-BI/blob/main/Superstore_Offline_Data.pbix)

Contains the complete Power BI report, including:

* Data model
* Power Query transformations
* DAX measures
* Calculated columns
* Interactive dashboards
* Charts and visualizations

### Dataset

[Superstore_Offline_Data.csv](https://github.com/Raghu5850/Superstore_offline-Data-Power-BI/blob/main/Superstore_Offline_Data.csv)

Contains the raw Superstore sales data used for the analysis.

### Screenshots

The `screenshots` folder contains images of the Power BI dashboard and important report pages.

---

## 🔄 Project Workflow

The project follows the following data analytics workflow:

### 1. Data Collection

Imported the Superstore offline dataset into Power BI.

### 2. Data Cleaning

Performed data cleaning and transformation using **Power Query**.

Activities included:

* Removing unnecessary columns
* Handling missing values
* Removing duplicate records
* Correcting data types
* Formatting date fields
* Standardizing categorical values
* Creating required columns

### 3. Data Transformation

Prepared the dataset for analysis by:

* Creating calculated fields
* Creating date-related fields
* Transforming sales and profit data
* Preparing dimensions for data modeling

### 4. Data Modeling

Created relationships between relevant tables and developed a structured Power BI data model.

The model was designed to support efficient reporting and analysis.

### 5. DAX Calculations

Created DAX measures to calculate important business metrics such as:

* Total Sales
* Total Profit
* Total Orders
* Total Quantity
* Average Sales
* Profit Margin
* Sales Growth
* Year-over-Year Sales
* Previous Year Sales

---

# 📈 Dashboard KPIs

The dashboard provides important Key Performance Indicators such as:

| KPI            | Description               |
| -------------- | ------------------------- |
| Total Sales    | Overall revenue generated |
| Total Profit   | Overall profit generated  |
| Total Orders   | Number of orders          |
| Total Quantity | Quantity of products sold |
| Average Sales  | Average sales per order   |
| Profit Margin  | Profitability percentage  |

---

# 📊 Dashboard Analysis

## 1. Sales Performance

Analyzed overall sales performance using:

* Year-wise sales
* Monthly sales trends
* Sales by category
* Sales by sub-category
* Sales by region
* Sales by state

This helps identify periods and locations with strong or weak sales performance.

---

## 2. Profit Analysis

Analyzed profitability using:

* Total profit
* Profit by category
* Profit by sub-category
* Profit by region
* Profit by state
* Profit by product

This helps identify profitable and loss-making areas of the business.

---

## 3. Product Analysis

Analyzed product-level performance to identify:

* Top-selling products
* Most profitable products
* Low-performing products
* Loss-making products
* Product categories generating the highest revenue

---

## 4. Customer Analysis

Analyzed customer performance based on:

* Total sales
* Total profit
* Number of orders
* Customer segment
* Geographic location

This helps identify valuable customers and customer segments.

---

## 5. Regional Analysis

Analyzed performance across different regions and locations.

The analysis includes:

* Sales by region
* Profit by region
* State-wise sales
* State-wise profit
* Geographic performance

---

# 🧮 Important DAX Measures

Some of the key measures created in this project include:

```DAX
Total Sales = SUM(Superstore[Sales])
```

```DAX
Total Profit = SUM(Superstore[Profit])
```

```DAX
Total Quantity = SUM(Superstore[Quantity])
```

```DAX
Total Orders = DISTINCTCOUNT(Superstore[Order ID])
```

```DAX
Profit Margin = 
DIVIDE([Total Profit], [Total Sales], 0)
```

Additional DAX measures were created for trend analysis and year-over-year comparisons.


# 🎨 Dashboard Features

The Power BI report includes:

* Interactive slicers
* KPI cards
* Bar charts
* Column charts
* Line charts
* Donut charts
* Maps
* Tables
* Drill-down functionality
* Cross-filtering
* Interactive navigation


# 🚀 Business Value

This Power BI project demonstrates how raw sales data can be transformed into an interactive business intelligence solution.

The dashboard enables users to quickly identify:

* Sales trends
* Profitability trends
* High-performing products
* Low-performing products
* Valuable customers
* Regional opportunities
* Areas requiring business attention

---

# 👨‍💻 Skills Demonstrated

Through this project, I demonstrated the following skills:

* Power BI
* Power Query
* DAX
* Data Cleaning
* Data Transformation
* Data Modeling
* Data Visualization
* KPI Development
* Business Intelligence
* Exploratory Data Analysis
* Dashboard Development
* Business Insights

---

# 📌 Conclusion

The **Superstore Offline Data Power BI project** demonstrates the complete analytics workflow, from raw data preparation and transformation to data modeling, DAX calculations, visualization, and business insights.

The final dashboard provides an interactive and user-friendly way to analyze sales and profitability and supports data-driven decision-making.
