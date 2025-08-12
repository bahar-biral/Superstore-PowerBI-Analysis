# 📊 Global Superstore Power BI Dashboard

## 📝 Project Overview
This project presents a comprehensive **sales, profitability, and geographic analysis** using the **Global Superstore** dataset in Power BI.  
It features **dynamic filtering, page navigation, advanced DAX calculations, and interactive visualizations** to create an intuitive and insightful dashboard.

***

## 🚀 Key Features
- **Slicer Panel**: Toggle all slicers on/off via a filter icon (created with bookmarks)
- **Page Navigation Icons**: Navigate between **Overview**, **Detailed Analysis**, and **Geographic Analysis** pages
- **Advanced DAX Measures**:
  - Most profitable customer
  - Most profitable state
  - Last year total profit
  - Last year total sales
  - Profit margin
  - Cumulative total profit / sales
  - Average order value
  - Average daily sales

***

## 📂 Page 1 - Overview
![Page 1 Overview](https://github.com/bahar-biral/Superstore-PowerBI-Analysis/blob/main/Overview.Page1.png?raw=true)

- **Total Sales by Year** *(Area Chart)*  
  From 2014–2017, sales increased each year, peaking in **November** annually.
- **Sales & Profit Trends** *(Line Chart)*  
  Sales show an overall upward trend; profit trend is less consistent.
- **Sales by Category** *(Bar Chart)* → Highest in **Technology**
- **Sales by Segment** *(Bar Chart)* → Highest in **Consumer**
- **Sales by Shipping Mode** *(Bar Chart)* → Highest in **Standard Class**
- **Top Profit Contributors**:  
  - Customer → Tamara Chand  
  - Product → Canon imageCLASS 2200 Advanced Copier  
  - State → California

***

## 📂 Page 2 - Detailed Analysis
![Page 2 Detailed Analysis](https://github.com/bahar-biral/Superstore-PowerBI-Analysis/blob/main/Detailed%20Analysis.Page2.png?raw=true)

- **This Year vs. Last Year Sales** → With time slicer for drill-down
- **Segment Performance**:
  - Highest sales → Consumer  
  - Highest YoY sales growth rate (%) → Home Office  
  - Highest profit margin → Home Office (slightly ahead)
- **Top 5 Most Profitable Products** → #1: Canon imageCLASS 2200 Advanced Copier (using Top N filter)
- **Bottom 5 Least Profitable Products** → #1: Bush Advantage Collection Racetrack Conference Table (using Bottom N filter)
- **Customer Analysis (Table)** → Identifying negative profit margin customers (e.g., Sean Miller with -7.91%)
- **Category & Subcategory Analysis (Bubble Chart)**:
  - Highest sales + profit margin → Technology → Phones
- **Profit Distribution (Bar Chart)**:
  - Categories below average profit highlighted in red (e.g., Furniture → Tables)

***

## 📂 Page 3 - Geographic Analysis
![Page 3 Geographic Analysis](https://github.com/bahar-biral/Superstore-PowerBI-Analysis/blob/main/Geographic%20Analysis.Page3%20(Tooltips).png?raw=true)

- **Sales & Profit by Region (Ribbon Chart)** → West region leads in sales every year
- **Map Visualization**:
  - Hover over a state to see:
    - Top 5 selling products in that state  
    - Most valuable customer  
  - Most profitable state → California

***

## 🛠 Techniques Used
- **Power BI Bookmarks** for dynamic slicer panel and page navigation
- **Advanced DAX calculations** for KPIs and performance metrics
- **Interactive tooltips** on maps for detailed state-level insights
- **Top N / Bottom N filtering** for profitability analysis
