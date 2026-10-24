 # 💳 Credit Card Financial Dashboard

## 📌 Project Overview

This project analyzes the performance of credit card customers using real transaction and customer data. The main goal of this project is to understand how revenue is generated, which customers spend the most, which cards are used the most, and how business is growing week by week.

This dashboard was created using Excel, MySQL and Power BI, and it helps the business to track weekly performance, customer behavior and overall revenue in one place.

---

## 🛠️ Tools Used

- 📊 Excel - For data collection and initial checking
- 🗄️ MySQL - For database creation, data cleaning and data storage
- 📈 Power BI - For dashboard creation, DAX calculation and visualization
- 🐙 GitHub - For project documentation

---

## 📂 Dataset

This project is based on 4 main files:

1. cc_detail.csv - This file contains credit card transaction details like card category, annual fees, transaction amount, transaction count, credit limit and week wise data
2. cust_detail.csv - This file contains customer details like age, gender, income, education, marital status, state and customer job
3. Credit Card Report SQL File - This file contains all SQL queries used to create tables and analyze data
4. Dashboard Data - This file contains the final data used in Power BI dashboard

---

## ⚙️ What I Did In This Project

### 1. Data Collection and Import - Excel to MySQL

First of all I collected data from Excel and CSV files. After checking the data, I imported it into MySQL. I created a database named ccdb and created two tables inside it.

First table was cc_detail and second table was cust_detail. Both tables were connected with each other using Client_Num. After that I imported all data from CSV files into these tables using LOAD DATA INFILE method.

### 2. Data Cleaning and Preparation

After importing data into MySQL, I cleaned the data. I fixed the date format, removed unnecessary columns, and set correct data types for all columns. I also created a new Week Number column from Week Start Date to analyze data week by week.

### 3. MySQL to Power BI Connection

After data was ready in MySQL, I connected it with Power BI. I used Import Mode to import data from MySQL to Power BI. I created a relationship between cc_detail and cust_detail tables on Client_Num so both tables can work together in the dashboard.

### 4. DAX Calculations

In Power BI I created many DAX formulas to calculate important business values.

I created Revenue formula by adding Annual Fees, Total Transaction Amount and Interest Earned. I created AgeGroup to divide customers into different age groups like 20-30, 30-40, 40-50, 50-60 and 60 plus. I created IncomeGroup to divide customers into Low, Med and High income groups. I also created Current Week Revenue and Previous Week Revenue formulas to compare week by week growth.

### 5. Dashboard Creation

After calculations were done, I created a professional dashboard in Power BI. I created 4 pages in the dashboard. First page was Summary Page for overall performance. Second page was Customer Page for customer analysis. Third page was Transaction Page for transaction analysis. Fourth page was Insights Page for week 53 analysis.

I used Cards, Bar Charts, Line Charts and Donut Charts to show data clearly.

### 6. New Files Added and Dashboard Update

This dashboard is not static, it updates every week. When new weekly files come, I import them into MySQL again, then I click Refresh All in Power BI, and the dashboard updates automatically with new data. This process was repeated for every new week, so the dashboard always shows latest data.

---

## 📈 Key Insights - Week 53 - 31st Dec

This section shows the most important findings of this project.

### Week on Week Growth

- 💰 Revenue increased by 28.8 percent in Week 53
- 📊 Transaction Amount and Transaction Count also increased
- 👥 Customer count also increased compared to previous week

### Overall Performance - Year To Date

- 💰 Overall Revenue is 57M
- 💵 Total Interest Earned is 8M
- 🛒 Total Transaction Amount is 46M
- 👨 Male Customers Revenue is 31M
- 👩 Female Customers Revenue is 26M
- 💳 Blue and Silver Card contributes 93 percent of total transactions
- 🗺️ TX, NY and CA states contributes 68 percent of total business
- ✅ Activation Rate is 57.5 percent
- ⚠️ Delinquent Rate is 6.06 percent

These insights show that revenue is growing, Blue card is the most popular card, male customers spend more than female customers, and top 3 states are giving most of the business.

---

## ✅ Conclusion

This project helped me to understand how credit card business works. Revenue is increasing week by week, Blue card is used the most, male customers spend more than female customers, and TX, NY and CA are the top performing states. This dashboard can help any business to track weekly performance, customer behavior and revenue growth easily.

This project also improved my skills in Excel, MySQL, Power BI, DAX and data visualization.

---

## 👩‍💻 Author

Created by a Data Analyst Learner
Tools Used - Excel, MySQL, Power BI

---

Thank you for visiting this project.
