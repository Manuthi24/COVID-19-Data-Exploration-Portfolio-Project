# 🌍 COVID-19 Data Exploration Portfolio Project

## 📌 Project Overview
This project is the **first part of a four-part Data Analyst portfolio series**. It involves an extensive **data exploration of global COVID-19 data** using **SQL Server**.  

The main goal is to **derive insights** regarding infection rates, death percentages, and vaccination progress across **different countries and continents**.  

---

## 🗂 Data Sources
The data used in this project was sourced from a **global COVID-19 dataset** covering the period from **January 1, 2020, to the present**.  

The data was separated into **two primary tables**:

| Table Name | Description |
|------------|-------------|
| `CovidDeaths` | Contains information on cases, deaths, and population. |
| `CovidVaccinations` | Contains information on new vaccinations and tests. |

---

## 🛠 Tools Used
- **MS SQL Server 2019**: Querying and data exploration  
- **MS Excel**: Initial data formatting and preparing files for import  
- **GitHub**: Repository hosting and version control  

---

## 💻 Key SQL Skills Demonstrated
This project showcases several **advanced SQL techniques**:

- **🔗 Joins**: Combine `CovidDeaths` and `CovidVaccinations` tables on `location` and `date`.  
- **🧩 CTEs (Common Table Expressions)**: Perform calculations on partitioned data, e.g., percentage of population vaccinated.  
- **📦 Temp Tables**: Store intermediate results for further calculations.  
- **📊 Window Functions**: Use `PARTITION BY` and `ORDER BY` to create rolling counts of new vaccinations.  
- **🧮 Aggregate Functions**: Use `SUM`, `MAX`, and `GROUP BY` to find highest infection counts and death rates per population.  
- **🔄 Data Type Conversion**: Use `CAST` and `CONVERT` for mathematical operations.  
- **👁 Creating Views**: Generate permanent views to store data for future visualizations in Tableau.  

---

## 📊 Project Insights
The data exploration answered several **key questions**:

- ⚠️ **Likelihood of dying** if you contract COVID-19 in a specific country  
- 🌡 **Percentage of a country's population infected**  
- 🏆 **Countries with the highest infection and death rates relative to population**  
- 🌎 **Global numbers** regarding total cases, deaths, and overall death percentage  

---

## 🔮 Future Work
The data prepared in this project (via **created views**) will be used in the **second project of the series**:  

- **Data Visualization using Tableau**  

---

## 📂 Repository Structure
```text
COVID-19-Data-Exploration/
│
├─ data/
│  ├─ CovidDeaths.csv
│  └─ CovidVaccinations.csv
│
├─ sql/
│  ├─ exploration_queries.sql
│  ├─ create_views.sql
│  └─ temp_tables.sql
│
├─ README.md
└─ LICENSE
