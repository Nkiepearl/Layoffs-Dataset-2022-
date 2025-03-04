# Layoffs Dataset (2022) - Data Cleaning & Exploratory Data Analysis  

## 📌 Project Overview  
This project analyzes the **2022 Layoffs Dataset** to identify trends in workforce reductions across different industries and countries. It includes **data cleaning** and **exploratory data analysis (EDA)** using SQL.  

## 📂 Table of Contents  
- [Description](#-description)  
- [Business Introduction](#-business-introduction)  
- [Business Problem](#-business-problem)  
- [Project Aim](#-project-aim)  
- [Process Taken](#-process-taken)  
- [Tools Used](#-tools-used)  
- [Key Insights](#-key-insights)  

---

## 📊 Description  
The dataset, sourced from Kaggle, contains company layoffs recorded in 2022.

---

## 💡 Business Introduction  
The global economy has seen major workforce reductions, particularly in tech and finance. By analyzing layoffs, businesses and policymakers can better understand employment trends, economic shifts, and industry stability.  

---

## 🔍 Business Problem  
Without structured data, it’s difficult to analyze workforce reductions. This project aims to:  
✔ Identify industries most affected by layoffs.  
✔ Understand correlations between layoffs and economic events.  
✔ Predict potential layoffs based on historical data.  

---

## 🎯 Project Aim  
- Identify trends based on industry, country, and company size.  
- Explore economic factors influencing layoffs.  
- Visualize layoff patterns using SQL queries.  
- Develop insights for workforce planning and economic policies.  

---

## 🛠 Process Taken  

### **🔹 Data Cleaning (SQL)**  
1. **Removing Duplicates** – Used `ROW_NUMBER()` to detect and delete duplicates.  
2. **Standardizing Data** – Trimmed spaces, standardized industry names, and corrected country names.  
3. **Handling Missing Values** – Filled missing industry names using related company data.  
4. **Formatting Dates** – Converted `date` column to proper `DATE` format.  

### **🔹 Exploratory Data Analysis (SQL)**  
✔ **Total Layoffs Analysis** – Identified companies & industries with the highest layoffs.  
✔ **Time-Based Trends** – Aggregated layoffs by year and month.  
✔ **Industry & Country Breakdown** – Compared layoff rates across industries and locations.  
✔ **Company Ranking** – Used `DENSE_RANK()` to rank layoffs by year.  
✔ **Rolling Layoff Trends** – Calculated cumulative layoffs over time.  

---

## 🛠 Tools Used  
- **Database:** MySQL  
- **Query Language:** SQL  
- **Platform:** Kaggle (Dataset Source)  

---

## 📈 Key Insights  
📌 **Tech Industry Layoffs:** The majority of layoffs occurred in the tech sector.  
📌 **Economic Impact:** Layoffs spiked during economic downturns.  
📌 **Country-Specific Trends:** Certain regions experienced higher layoffs due to market conditions.  
📌 **Time-Based Analysis:** Peaks in layoffs were observed in specific months.
