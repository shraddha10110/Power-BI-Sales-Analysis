# 📊 Power BI Sales Analysis Dashboard

## 🚀 Project Overview  
This project focuses on analyzing sales performance using **Power BI**.  
The goal is to help businesses understand key trends in revenue, customer behavior, product performance, and seasonal variations.  
The dashboard provides interactive visuals, slicers, KPIs, and drill-down features that allow stakeholders to make data-driven decisions quickly.
## 🛠 Tools Used  
- **Power BI Desktop**  
- **Power Query** (Data Cleaning & Transformation)  
- **DAX** (Measures & Calculations)  
- **Excel/CSV Dataset**  
- **Data Modeling (Star Schema)**  
## 📂 Repository Structure  
PowerBI-Sales-Analysis/
│
├── Dataset/
│ └── (dataset .xlsx or .csv)
│
├── PowerBI File/
│ └── Sales_Dashboard.pbix
│
├── Dashboard-Screenshots/
│ └── screenshot_1.jpg
│ └── screenshot_2.jpg
│
├── README.md
│
├── LICENSE
└── .gitignore
## 📈 Dashboard Features  
### **✨ Interactive KPIs**
- Total Revenue  
- Total Customers  
- Average Order Value  
- Profit Margin  
### **📊 Visualizations Included**
- Revenue trend line chart (Monthly/Yearly)  
- Category-wise and product-wise performance  
- Region & state-wise transactions  
- Top 5 & bottom 5 products  
- Slicers: Category, State, Customer Segment, Date  
### **🧭 Data Model (Star Schema)**
- **Fact Table:** Sales  
- **Dimension Tables:** Products, Customers, Calendar, Region  
## 🧮 Key DAX Measures  
Total Sales = SUM(Sales[Sales Amount])

Total Quantity = SUM(Sales[Quantity])

Average Order Value = DIVIDE([Total Sales], [Total Orders])

Sales YoY% = 
DIVIDE([Total Sales] - [Sales LY], [Sales LY])
 
## 🖼 Dashboard Preview
Dashboard-Screenshots/Screenshot 2025-11-24 173301.png
