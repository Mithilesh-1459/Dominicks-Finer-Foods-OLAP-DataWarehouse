# 📦 Data Warehouse Design and Implementation for Dominick’s Finer Foods (DFF)

## 📖 Introduction

Dominick’s Finer Foods (DFF), founded in 1918, was a major grocery store chain in Chicago. This project focuses on designing and implementing a **data warehouse** for DFF using store-level data from **1989 to 1994**.  

The goal is to consolidate scattered data sources, ensure data quality, and create a historical view of operations to drive **customer behavior analysis**, **sales trend identification**, and **strategic decision-making**. This project also delivers business intelligence (BI) reporting tailored for actionable insights.

---

## 🎯 Business Questions Addressed
- Which store had the highest customer traffic in the last quarter of 1994?
- During 1991 and 1992, which holiday week saw the highest grocery sales in Buffalo Grove’s low-tier stores?
- How does the profit margin of toothpaste vary by brand?
- What are the monthly average sales across Bakery, Dairy, Pharmacy, Cosmetic, and HABA departments in Naperville and Schaumburg stores during 1994?
- What were the highest sales contributions from single and retired individuals in Buffalo Grove stores for Budweiser Beer during Thanksgiving week 1993?

📄 *Detailed answers and insights are provided in the full project report.*

---

## 🛠️ Tools and Technologies Used
- **SQL Server 2019** – Data Warehouse and Data Marts
- **Visual Studio 2022**
- **SSMS (SQL Server Management Studio)** – Database and staging area management
- **SSIS (SQL Server Integration Services)** – Building ETL pipelines
- **SSAS (SQL Server Analysis Services)** – Multidimensional cube design
- **Power BI** – Visualization and dashboard creation
- **Tableau** – Additional BI reporting
- **Report Builder** – Formal report generation

---

## 🏗️ Key Features and Implementation Steps
- Adopted **Kimball’s dimensional modeling methodology**.
- Designed a **staging area** for initial data ingestion and validation.
- Built **fact** and **dimension tables** following star schema design.
- Created **ETL pipelines** in SSIS to:
  - Extract data from CSVs, Excel, and legacy systems
  - Perform data cleaning and transformations
  - Load into data marts.
- Addressed **data quality issues** like missing values, inconsistent codes, and granularity mismatches.
- Constructed **OLAP cubes** in SSAS for efficient multidimensional analysis.
- Delivered **interactive reports and dashboards** using Power BI and Tableau.

---

## 📊 Data Sources Overview
- **Customer Count Files** – Daily customer traffic, sales, and coupon usage data
- **Store Demographic Files** – Socio-economic profiles of store trading areas (age, income, education, shopping behavior)
- **UPC Files** – Product metadata including brand, category, and description
- **Movement Data Files** – Weekly sales, price, quantity, and margin data by product and store

Data was primarily sourced from the **James M. Kilts Center at University of Chicago Booth School of Business**&#8203;:contentReference[oaicite:3]{index=3}.

---

## 🔒 Copyright Notice and Disclaimer

© 2025 Mithilesh Menakuru. All Rights Reserved.  

This document, including its contents, implementation designs, diagrams, and any associated intellectual property, is the sole and exclusive property of **Mithilesh Menakuru**.  
Unauthorized use, reproduction, distribution, modification, or transmission of any part of this document or its related materials is strictly prohibited without prior written consent.  
Violations will be treated as plagiarism and legal action may be pursued accordingly.

---

## ✨ Acknowledgements
- **Dominick’s Finer Foods (DFF)** for providing historical datasets.
- **James M. Kilts Center for Marketing** at the University of Chicago Booth School of Business for maintaining the database.

---
