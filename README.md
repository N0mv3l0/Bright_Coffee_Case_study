# Bright_Coffee_Case_study


# ☕ Bright Coffee Shop Sales Analysis

## 📌 Project Overview

The **Bright Coffee Shop Sales Analysis** is an end-to-end Business Intelligence and Data Analytics case study that analyzes transactional sales data from a coffee shop chain with **three store locations**. The objective was to transform raw sales data into meaningful business insights through data cleaning, exploratory data analysis (EDA), interactive dashboards, and executive reporting.

The project demonstrates the complete analytics lifecycle—from understanding the business problem and preparing the data to building dashboards and developing an AI-powered data agent capable of answering business questions.

The analysis focuses on identifying sales trends, evaluating store performance, measuring product performance, and understanding customer purchasing patterns over time to support data-driven decision-making.

---

## 🎯 Project Objectives

* Clean and prepare the sales dataset for analysis.
* Perform Exploratory Data Analysis (EDA) using SQL.
* Calculate key business performance metrics.
* Compare sales performance across coffee shop locations.
* Analyze product categories and product types.
* Identify monthly and daily sales trends.
* Develop interactive dashboards for executive reporting.
* Build a conversational Data Agent capable of answering business questions using natural language.

---

## 📊 Dataset Overview

The dataset contains transactional sales information, including:

* Transaction ID
* Transaction Date
* Store Location
* Product Category
* Product Type
* Quantity Sold
* Unit Price
* Revenue (calculated)

**Calculated Metrics**

* Revenue = Unit Price × Quantity Sold
* Average Transaction Value
* Revenue by Store
* Revenue by Product Category
* Revenue by Product Type
* Monthly Revenue
* Weekday vs Weekend Sales

---

# 🔍 Exploratory Data Analysis (EDA)

The dataset was cleaned and transformed using SQL in Databricks.

Data preparation included:

* Removing duplicate transactions
* Creating calculated revenue fields
* Creating Month Name, Day Name and Day Number columns
* Categorizing transactions into Weekday and Weekend sales
* Consolidating similar tea products into a single sub-category
* Generating summary tables for reporting

The EDA focused on answering key business questions such as:

* Which store generates the highest revenue?
* Which products contribute the most sales?
* How do sales change over time?
* Which days experience peak sales?
* What are the highest-performing product categories?

---

# 📈 Dashboard Features

The dashboards provide both executive-level and operational insights.

### Executive KPIs

* 💰 Total Revenue
* 🛒 Total Items Sold
* 🧾 Total Transactions
* 💵 Average Transaction Value
* 📦 Average Items per Transaction

### Sales Performance

* Revenue by Store Location
* Monthly Revenue Trend
* Revenue Contribution by Store

### Product Performance

* Revenue by Product Category
* Top Selling Product Types
* Quantity Sold by Product
* Product Category Contribution

### Time Analysis

* Revenue by Month
* Revenue by Day of Week
* Weekday vs Weekend Performance
* Daily Sales Trend

---

# 🤖 Coffee Shop Data Agent
https://dbc-f0761396-3c73.cloud.databricks.com/genie/rooms/01f182138e5e1115946505c66746aecf?o=7474658285210116

A conversational AI assistant was developed to answer business questions using the coffee shop dataset.

The Data Agent can answer questions such as:

* Which store generated the highest revenue?
* What is the total revenue this month?
* Which product category performs best?
* Compare sales between store locations.
* Which products should management prioritize?
* How do weekday and weekend sales compare?

The agent provides:

* Direct answers
* Supporting metrics
* Evidence-based insights
* Actionable recommendations
* Transparent reporting when information is unavailable

---

# 🛠️ Tools Used

| Tool                     | Purpose                                                               |
| ------------------------ | --------------------------------------------------------------------- |
| **Databricks**           | SQL-based data cleaning, EDA, KPI calculations and dashboard creation |
| **Microsoft Excel**      | Dashboard development and pivot table analysis                        |
| **Power BI**             | Interactive business intelligence dashboard                           |
| **Google Looker Studio** | Cloud-based interactive dashboard and reporting                       |
| **Lovable**              | AI-generated interactive executive dashboard 
|                            https://bright-coffee-shop-analysis-dashboard.lovable.app             |
| **Canva**                | Project planning using a Gantt Chart                                  |
| **Miro**                 | Brainstorming, process mapping and project flowchart design           |

---

# 💡 Key Business Insights

* Store performance varied across the three locations, highlighting opportunities to benchmark successful operational practices.
* Coffee beverages generated the largest share of revenue, confirming they are the core drivers of sales.
* A small number of product types contributed disproportionately to overall revenue, suggesting that inventory planning should prioritize these high-performing items.
* Sales patterns differed across weekdays and weekends, indicating opportunities to optimize staffing levels and promotional activities based on customer demand.
* Monthly sales trends revealed periods of stronger and weaker performance, providing management with a basis for seasonal planning and targeted marketing campaigns.
* Consolidating similar tea products into a single category simplified reporting and enabled clearer comparisons across beverage categories.

---

# 📚 Skills Demonstrated

* SQL
* Exploratory Data Analysis (EDA)
* Data Cleaning
* Data Transformation
* Business Intelligence
* Dashboard Design
* KPI Development
* Data Storytelling
* Interactive Reporting
* AI Prompt Engineering
* Conversational Analytics
* Business Recommendation Development

---

# 🚀 Project Outcome

This project demonstrates the ability to transform transactional sales data into actionable business intelligence through a combination of SQL, visualization tools, and AI-assisted analytics. By integrating multiple dashboarding platforms with a conversational Data Agent, the solution enables executives and operational managers to explore key performance indicators, identify sales trends, evaluate store and product performance, and make informed business decisions based on reliable, data-driven insights.






