# ott-platform-performance-

## 📌 Project Overview

This project focuses on analyzing subscriber growth and revenue trends of Netflix OTT platform using SQL.
The goal is to extract meaningful insights from raw data and understand regional performance, user growth, and revenue patterns.

---

## 📂 Dataset Description

The dataset contains information about:

* Date (monthly data)
* Subscribers across regions:

  * US & Canada
  * Europe & Africa
  * Latin America
  * Asia Pacific
* Revenue generated from each region
* Average Revenue Per User (ARPU)

---

## 🧹 Data Cleaning

The following data cleaning steps were performed:

* Extracted **Month** and **Year** from the date column
* Created a **Quarter** column (Q1, Q2, Q3, Q4)
* Converted month into text format
* Renamed columns for better readability and consistency

These steps ensured the dataset was structured and ready for analysis.

---

## 📊 Data Analysis

Performed SQL-based analysis to answer key business questions:

### 🔹 Subscriber Analysis

* Identified highest subscribers per region and year
* Analyzed growth trends across different regions

### 🔹 Revenue Analysis

* Determined highest revenue-generating quarters
* Compared regional revenue contributions

### 🔹 ARPU Analysis

* Found regions with highest average revenue per user
* Compared ARPU trends over time

### 🔹 Yearly Trends

* Calculated total subscribers per year
* Ranked yearly revenue using SQL window functions

---

## 🛠️ SQL Concepts Used

* SELECT, WHERE, GROUP BY, ORDER BY
* Aggregate Functions (SUM, AVG)
* Window Functions:

  * FIRST_VALUE()
  * RANK()
* CASE Statements
* Data Extraction Functions (EXTRACT, TO_CHAR)
* Subqueries

---

## 📈 Key Insights

* Certain regions consistently contribute higher revenue
* Subscriber growth varies significantly across regions
* ARPU trends highlight differences in pricing and user behavior
* Specific quarters show peak performance in both revenue and subscribers

---

## 🧰 Tools Used

* SQL (PostgreSQL/MySQL)

---

## 📌 Conclusion

This project demonstrates how SQL can be used to clean, transform, and analyze real-world datasets.
It highlights the importance of data-driven decision-making in understanding business performance.

