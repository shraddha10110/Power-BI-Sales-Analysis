# 📊 Power BI Sales Analysis Dashboard

## 🚀 Project Overview
This project analyzes sales performance using Power BI. It includes KPI tracking, trend analysis, product performance breakdown, customer insights, and fully interactive dashboards designed for business decision-making.

---

## 🛠 Tools Used
- Power BI Desktop  
- Power Query  
- DAX  
- Excel / CSV Dataset  
- Data Modeling (Star Schema)

---

## 📂 Folder Contents
- **Dataset/** → Cleaned dataset in CSV/XLSX  
- **PowerBI File/** → .pbix file  
- **Dashboard-Screenshots/** → Dashboard images  
- **Insights/** → Summary report  
- **Docs/** → Data dictionary (optional)

---

## 📈 Dashboard Highlight Features
- KPI cards: Total Revenue, Total Profit, Return Count  
- Year selector slicers  
- Product category performance table  
- Region-wise revenue map  
- State-wise transactions tree map  
- Month-on-month growth analysis using DAX

---

## 🧮 Key DAX Measures

Total Sales = SUM(Sales[SalesAmount])

Total Profit = SUM(Sales[Profit])

Profit Margin = DIVIDE([Total Profit], [Total Sales])

YOY Growth = CALCULATE([Total Sales], DATEADD(Sales[Date], -1, YEAR))
