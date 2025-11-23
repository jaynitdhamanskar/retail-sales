# Retail Sales Analysis SQL Project

# Project Overview

**Project Title:** Retail Sales Analysis

This project showcases essential SQL skills used by data analysts to explore, clean, and analyze retail sales data. It covers database setup, data validation, exploratory data analysis, and business-focused insights. This project is ideal for beginners who want to strengthen their SQL foundation with a real-world retail dataset.

## Objectives

* **Database Setup:** Create a structured retail sales database and load transaction data.
* **Data Cleaning:** Identify invalid or missing records and ensure dataset reliability.
* **Exploratory Data Analysis (EDA):** Understand customer demographics, product categories, and sales patterns.
* **Business Insights:** Answer key business questions related to customer behavior, product performance, and sales trends.

## Project Structure

### 1. Database Setup

* The project begins by creating a SQL database and defining a table to store retail transactions.
* The dataset includes details such as transaction ID, date/time, customer demographics, product category, pricing, and sales amount.

### 2. Data Exploration & Cleaning

* Initial exploration determines total records, customers, and product categories.
* The dataset is checked for missing or null values.
* Invalid rows are identified and removed to ensure accuracy.

### 3. Analysis Performed

The project includes analysis such as:

* Daily sales lookup
* Category‑wise sales trends
* Average age analysis for category buyers
* High‑value transaction identification
* Gender‑wise purchase patterns
* Monthly average sales and best‑performing months
* Top‑spending customers
* Unique customer counts per product category
* Order distribution across Morning, Afternoon, and Evening shifts

---

## Findings

Based on the uploaded dataset and SQL outputs, the following insights were observed:

### **1. Category Performance**

* **Electronics:** Net sales of **311,445** across **678 orders**.
* **Clothing:** Net sales of **309,995** across **698 orders**.
* **Beauty:** Net sales of **286,790** across **611 orders**.

Clothing and Electronics are the strongest categories in terms of both sales volume and order count.

### **2. Customer Demographics**

* The **average customer age** for Beauty category buyers is **40.41 years**.
* Customer distribution across categories is balanced between Male and Female shoppers.

### **3. Gender–Category Insights**

Number of transactions:

* **Female – Beauty:** 330
* **Female – Clothing:** 347
* **Female – Electronics:** 335
* **Male – Beauty:** 281
* **Male – Clothing:** 351
* **Male – Electronics:** 343

Overall, Clothing has strong engagement from both genders.

### **4. Monthly Sales Trends**

Best-performing months by average sale:

* **July 2022:** Avg sale **541.34**
* **February 2023:** Avg sale **535.53**

These periods represent seasonal performance peaks.

### **5. Top Customers**

Highest spending customers:

* Customer **3:** 38,440
* Customer **1:** 30,750
* Customer **5:** 30,405
* Customer **2:** 25,295
* Customer **4:** 23,580

A small group of customers contribute significantly to overall revenue.

### **6. Unique Customer Count per Category**

**Clothing:** 149 unique customers
**Electronics:** 144 unique customers
**Beauty:** 141 unique customers

This indicates evenly spread customer engagement across all product types.

### **7. Order Distribution by Time of Day**

**Evening:** 1,062 orders (highest activity)
**Morning:** 548 orders
**Afternoon:** 377 orders

Evenings are the peak shopping period, likely due to customer availability.

## Reports Generated

* **Sales Summary Report:** Overview of category‑wise sales, order volume, and revenue distribution.
* **Customer Insights Report:** Top customers, unique customers per category, and demographic observations.
* **Trend Analysis Report:** Monthly performance, shift‑based ordering, and seasonal behaviors.

## Conclusion

This project provides a complete end‑to‑end SQL analysis workflow. It strengthens foundational SQL skills such as aggregation, grouping, filtering, and date/time functions. The insights gained can support decisions in customer targeting, inventory planning, and sales optimization.
