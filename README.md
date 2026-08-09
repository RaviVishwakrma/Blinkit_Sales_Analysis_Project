# Blinkit Sales Analysis Project

End-to-end Data Analysis & Dashboard project on Blinkit grocery dataset.  
This project demonstrates how raw retail data can be cleaned, analyzed, and visualized to generate actionable business insights.

## 🎯 Objective
To analyze Blinkit grocery sales data and uncover insights on outlet performance, product contribution, and customer preferences.  
The project showcases an end-to-end workflow: **Data Cleaning → EDA → Feature Engineering → Tableau Dashboard → Insights.**

## 🔑 Project Steps
1. **Understanding the Data**  
   - Explored dataset structure, columns, and missing values.  
   - Identified key fields: Item details, Outlet details, Sales metrics.

2. **Data Cleaning**  
   - Handled nulls (Item Weight, Outlet Size).  
   - Corrected data types (Years of Operation, categorical fields).  
   - Removed inconsistencies in Item Fat Content.

3. **Feature Engineering**  
   - Created `Sales_per_Item` metric.  
   - Derived `Years_of_Operation` from establishment year.  
   - Added `delivery_time_days` for delivered orders.

4. **Exploratory Data Analysis (EDA)**  
   - Distribution plots for Item MRP, Sales per Item.  
   - Category-wise analysis (Item Type, Fat Content).  
   - Outlet performance comparison across types and locations.  
   - Pricing trends and visibility impact.

5. **Dashboard Creation (Tableau)**  
   - Built KPIs and interactive charts for quick insights.  
   - Combined categorical, numerical, distribution, and trend analysis.

## 📈 KPIs
- **Total Sales** → ₹1,85,91,125  
- **Average Sales per Outlet**  2,181.29
- **Number of Outlets** is 10

## 📊 Key Insights
- **Supermarket Type3 outlets** generated the highest sales (~35% of total revenue).  
- **Tier 3 locations** outperformed Tier 1 & Tier 2 in average sales.  
- **Snack Foods** contributed the largest share (~20% of total sales).  
- Most items fall below **₹200 per unit sales**, showing a right-skewed distribution.  
- **Older outlets (10+ years)** show steady sales growth compared to newer ones.  
- Customer preference: **Low Fat items** slightly outsell Regular Fat items.

## 🛠 Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Jupyter Notebook**: Data cleaning & EDA  
- **Tableau**: Dashboard & KPIs  