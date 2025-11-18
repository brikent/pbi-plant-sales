# Year-to-Date Sales Analysis — Power BI Project

This project is a simple, clean Power BI report focused on comparing **Year-to-Date (YTD)** and **Prior Year-to-Date (PYTD)** performance across different KPIs. I used a public dataset and followed the general structure from the YouTube video *“The Only Power BI Portfolio Project You Need”*, but all modeling, DAX, and visual design were built by me.

---

## 📁 Data Modeling

I organized the data into a basic dimensional model (star schema) and created a clear semantic layer for analysis.

**Steps completed:**
- Loaded and renamed tables (`Dim_` and `Fact_`)
- Cleaned data types and formatted all currency fields  
- Built relationships between Dim and Fact tables  
- Added a custom `Dim_Date` table and linked it to `Fact_Sales`
- Created a dedicated Measures table  
- Wrote base measures (Sales, COGS, Gross Profit)
- Created **YTD**, **PYTD**, and variance measures  
- Added a **Switch Table** to toggle between KPIs  
- Organized measures into folders: *Base*, *YTD*, *PYTD*, and *Switch*

### 📸 Data Model Screenshot
*(Insert image in your repo and update the file name below)*  
`![Data Model](model.png)`

---

## 📊 Report Visuals

The report focuses on performance comparison and quick insight.

**Visuals included:**
- KPI cards for YTD, PYTD, and YTD vs PYTD  
- A Year slicer + a KPI slicer (Sales, Quantity, Gross Profit)
- YTD vs PYTD bar chart by product type  
- Monthly waterfall chart showing contribution over time  
- Clean title/header and consistent formatting throughout

### 📸 Dashboard Screenshot
*(Insert image in your repo and update below)*  
`![Dashboard](dashboard.png)`

---

## 🔎 What This Shows

- Solid understanding of Power BI data modeling  
- Practical time-intelligence using DAX  
- Clean semantic layer with organized measures  
- Ability to build reusable KPI-switching logic  
- Dashboard design geared toward executive-style insights  

---

## 🎥 Reference Video
[ *The Only Power BI Portfolio Project You Need*](https://www.youtube.com/watch?v=BLxW9ZSuuVI&t=3456s)

---

## 📦 Files Included
- `![Year to Date Plant Sales Analysis](Year to Date Plant Sales Analysis.pbix)` — full Power BI report  
- `![README.md](README.md)` — project overview  
