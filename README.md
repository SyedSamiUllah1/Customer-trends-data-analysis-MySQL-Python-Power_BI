# 🛍️ Customer Behaviour Data Analysis

An end-to-end Data Analytics project that analyzes customer purchasing behavior using **Python, MySQL, SQL, and Power BI**. The project demonstrates the complete analytics workflow—from data cleaning and preprocessing to database querying and interactive dashboard development.

---

## 📌 Project Overview

The objective of this project is to analyze customer purchasing patterns and generate actionable business insights by:

- Cleaning and preprocessing raw customer data using Python.
- Importing the cleaned dataset into MySQL.
- Performing exploratory and business-focused SQL analysis.
- Building an interactive Power BI dashboard for visualization.

---

## 🛠️ Tech Stack

- **Python**
  - Pandas
  - NumPy
  - SQLAlchemy
- **Jupyter Notebook**
- **MySQL Workbench**
- **SQL**
- **Power BI**
- **Git & GitHub**

---

# 📂 Project Structure

```
Customer-Behaviour-Data-Analysis
│
├── Customer_Behaviour_Analysis.ipynb
├── customer_data.csv
├── Customer_Behaviour_Dashboard.pbix
├── SQL_Queries.sql
├── README.md
│
└── Project_4_Screenshots
      ├── py1.png
      ├── py2.png
      ├── ...
      ├── py8.png
      ├── sql1.png
      ├── sql2.png
      ├── ...
      ├── sql10.png
      └── power_bi.png
```

---

# 🧹 Data Cleaning (Python)

The dataset was cleaned using **Pandas** before loading it into MySQL.

### Cleaning Steps

- Imported dataset
- Checked missing values
- Removed duplicate records
- Filled missing Review Ratings using category median
- Standardized column names
- Corrected data types
- Exported cleaned dataset

### Python Screenshots

#### Import Dataset

![](Project_4_Screenshots/py1.png)

#### Checking the Dataset

![](Project_4_Screenshots/py2.png)

#### Checking for Missing Values

![](Project_4_Screenshots/py3.png)

#### Missing values treatment

![](Project_4_Screenshots/py4.png)

#### Changing column names for easyness

![](Project_4_Screenshots/py5.png)

#### Creating new column

![](Project_4_Screenshots/py6.png)

#### Creating new column

![](Project_4_Screenshots/py7.png)

#### Ready for SQL

![](Project_4_Screenshots/py8.png)

---

# 🗄️ Database (MySQL)

The cleaned CSV was imported into MySQL Workbench where SQL queries were performed to answer business questions.

---

## SQL Analysis

The following analyses were performed:

- Revenue by Gender
- High Value Customers using Discounts
- Top Rated Products
- Average Purchase Amount by Shipping Type
- Subscription Status Analysis
- Products with Highest Discount Usage
- Customer Segmentation
- Top Selling Products within Categories
- Repeat Buyers
- Revenue Contribution by Age Group

---

## SQL Query Screenshots

### Query 1

![](Project_4_Screenshots/sql1.png)

### Query 2

![](Project_4_Screenshots/sql2.png)

### Query 3

![](Project_4_Screenshots/sql3.png)

### Query 4

![](Project_4_Screenshots/sql4.png)

### Query 5

![](Project_4_Screenshots/sql5.png)

### Query 6

![](Project_4_Screenshots/sql6.png)

### Query 7

![](Project_4_Screenshots/sql7.png)

### Query 8

![](Project_4_Screenshots/sql8.png)

### Query 9

![](Project_4_Screenshots/sql9.png)

### Query 10

![](Project_4_Screenshots/sql10.png)

---

# 📊 Power BI Dashboard

The final dashboard provides an interactive overview of customer purchasing behavior.

### Features

- KPI Cards
- Revenue Analysis
- Category Performance
- Age Group Analysis
- Subscription Analysis
- Interactive Filters
- Customer Distribution

### Dashboard

![](Project_4_Screenshots/power_bi.png)

---

# 📈 Key Insights

- Clothing generated the highest overall revenue.
- Adult customers contributed the largest share of revenue.
- Customers with subscriptions generated higher total revenue.
- Average purchase amount was **$59.76**.
- Average customer review rating was **3.75**.
- Revenue distribution varied significantly across product categories.

---

# 🚀 Skills Demonstrated

- Data Cleaning with Pandas
- Feature Engineering
- SQL Query Writing
- Common Table Expressions (CTEs)
- Window Functions
- Business Analysis
- Dashboard Design
- Data Visualization
- Power BI
- GitHub Documentation

---

# 👤 Author

**Syed Sami Ullah**

- GitHub: https://github.com/SyedSamiUllah1
- LinkedIn: www.linkedin.com/in/syed-sami-ullah-9232602a6

---

⭐ If you found this project helpful, consider giving it a star!
