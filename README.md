#  Sakila Video Rental — SQL Exploratory Data Analysis (EDA)

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on the sample **Sakila DB** using relational SQL queries within a Jupyter Notebook environment. The primary objective is to evaluate operational performance and rental volume distribution across three core dimensions: **individual titles**, **film categories**, and **store locations**.

---

## Key Findings & Analytical Takeaways

### 1. Film Rental Performance
* **Uniform Demand:** Rental volume across individual film titles shows a smooth, well-distributed spread without reliance on a single blockbuster title.
* **Lack of Outliers:** No specific films dominate inventory utilization, indicating consistent customer demand across the entire catalog.

### 2. Category / Genre Distribution
* **Balanced Genre Interest:** Aggregate rental counts across all 16 film categories range narrowly from **1,179 rentals** (*Sports*) to **830 rentals** (*Music*).
* **Broad Catalog Appeal:** While top genres (*Sports*, *Animation*, *Action*) perform slightly better, no single category overwhelmingly drives overall volume, suggesting a diversified customer preference.

### 3. Store Location Comparison
* **Equal Operational Load:** Rental transactions are almost evenly split between physical locations:
  * **Store 1:** 7,923 rentals (~49.4%)
  * **Store 2:** 8,121 rentals (~50.6%)
* **Balanced Demand:** Neither location serves as a primary hub or outpaces the other significantly (<2.5% variance), reflecting balanced customer foot traffic and inventory management.

---

##  Tools & Technologies
* **Database:** Sakila Sample Database (MySQL)
* **Query Language:** SQL (Multi-table joins, Aggregations, Grouping, Sorting)
* **Environment:** Jupyter Notebook (`ipython-sql` extension)

---

## Repository Structure
```text
├── Sakila_EDA.ipynb      # Main Jupyter Notebook containing SQL queries and commentary
├── README.md             # Project documentation and summary of findings
