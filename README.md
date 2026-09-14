# Customer Shopping Behaviour Analysis

## Project Overview

This project analyzes customer shopping behaviour using **Python (Pandas), MySQL, and Power BI**.

The project follows an end-to-end data analytics workflow:

**Data Cleaning & Manipulation → SQL Data Analysis → Business Insights → Power BI Dashboard**

The main objective is to understand customer purchasing patterns, spending behaviour, discounts, subscriptions, payment methods, and purchase frequency.

---

## Tools & Technologies

- **Python**
- **Pandas**
- **MySQL**
- **SQLAlchemy / PyMySQL**
- **Power BI**
- **Jupyter Notebook**

---

## Dataset

The dataset contains customer shopping behaviour information, including:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

---

## Project Workflow

### 1. Data Cleaning & Manipulation using Python

Python Pandas was used to prepare the dataset before analysis.

The data preparation included:

- Loading the dataset using Pandas
- Checking the structure and columns
- Checking missing values
- Handling missing Review Ratings using category-wise median values
- Standardizing column names
- Renaming columns for easier analysis
- Creating an `age_group` column
- Converting purchase frequency into purchase-frequency days
- Comparing discount and promo-code information
- Removing redundant information where appropriate
- Checking the final dataset before SQL analysis

### 2. Connecting Python with MySQL

After cleaning the dataset, the prepared data was connected to **MySQL** using:

- SQLAlchemy
- PyMySQL

This allowed the cleaned dataset to be stored and analyzed using SQL.

### 3. SQL Business Analysis

SQL was used to answer business-related questions and generate useful insights from the cleaned customer data.

The analysis focused on areas such as:

- Customer purchasing behaviour
- Category performance
- Customer spending
- Age-group behaviour
- Subscription status
- Discount usage
- Payment methods
- Purchase frequency
- Review ratings
- Shipping preferences
- Previous purchase behaviour

SQL techniques used include:

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- Aggregate Functions
- CASE Statements
- JOIN
- Subqueries
- Window Functions

### 4. Power BI Dashboard

The analyzed data was then used in **Power BI** to create an interactive dashboard.

The dashboard is designed to provide a visual overview of:

- Total customers
- Purchase and spending trends
- Category-wise performance
- Customer segmentation
- Subscription behaviour
- Discount usage
- Purchase frequency
- Payment methods
- Customer ratings
- Other important business insights

Interactive visuals and filters help users explore customer behaviour from different perspectives.

---

## Key Business Objectives

The project aims to answer questions such as:

- Which customer groups contribute more to purchases?
- Which categories have higher customer demand?
- How does subscription status relate to purchasing behaviour?
- How frequently do customers make purchases?
- Which payment methods are commonly used?
- How are discounts used by customers?
- Which age groups show different purchasing patterns?
- What factors can help a business understand customer behaviour better?

---

## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Python Pandas
- SQL
- MySQL
- Database Connectivity
- Business Question Analysis
- Data Visualization
- Power BI Dashboard Development

---

## Project Structure

```text
Customer-Shopping-Behaviour-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── customer_behavior_analysis.ipynb
│
├── SQL/
│   └── customer_behavior_analysis.sql
│
├── PowerBI/
│   └── customer_behavior_dashboard.pbix
│
└── README.md
```

---

## Conclusion

This project demonstrates an end-to-end data analytics workflow, starting from raw customer data and progressing through data cleaning, database analysis, business-question solving, and dashboard creation.

By combining **Python, SQL, and Power BI**, the project converts raw customer shopping data into meaningful business insights that can support better understanding of customer behaviour and decision-making.
