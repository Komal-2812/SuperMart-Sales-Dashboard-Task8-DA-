# 📊 Task 8: Interactive Sales Dashboard – Supermart Grocery Sales

## 📌 Objective
Design a clean, interactive sales dashboard that helps analyze:
- Sales trends over time
- Regional performance
- Category-wise breakdown
Using Power BI with proper data transformation, visualizations, and KPI cards.

---

## 🗃 Dataset
**Name**: Supermart Grocery Sales – Retail Analytics Dataset  
**Columns Used**:
- Order Date
- Region
- Category & Sub-Category
- Sales
- Profit
- Customer Info
- State / City

---

## 🛠 Tools & Technologies
- **Power BI Desktop** (for data modeling & dashboard)
- **DAX** (for KPI calculations)
- **Data Cleaning & Transformation** (in Power BI Power Query)

---

## 🧹 Data Preparation Steps
- Converted `Order Date` to Month-Year, Year, and Month columns
- Added calculated columns for sorting (Month Number)
- Ensured proper data types (Date, Currency, Text)
- Created DAX measures for KPIs like total sales, average profit, top region, etc.
- Removed blank and duplicate entries

---

## 📊 Dashboard Structure

### 🏠 **Home Page**
- Navigation Buttons: 🏠 Home | 📈 Sales Trend | 🌍 Region | 🗂 Category
- KPIs:
  - 💰 Total Profit: 3.75M
  - 📅 Date Range: Jan 2015 – Dec 2018
  - 📦 Total Records: 9,994
- Welcome message and Q&A integration
- Overview: interactive entry point to explore all metrics

---

### 📈 **Sales Trend Page**
- Line Chart: Monthly Sales
- Line Chart: Monthly Profit
- Slicers: Region, Category, Month-Year
- KPIs:
  - 📦 Total Sales
  - 📈 Avg Monthly Sales
  - 💸 Total Profit

---

### 🌍 **Region Analysis Page**
- Bar Chart: Sales by Region
- Donut Chart: Profit by Region
- Line & Column Chart: Sales vs Profit by Year and Region
- Table: Category-wise Sales per Region
- Slicers: Month-Year, Category
- KPIs:
  - Top Performing Region: **West**
  - Profit by Region
  - Discount Trends

---

### 🗂 **Category Analysis Page**
- Donut Chart: Sales by Category
- Matrix: Sub-Category Sales and Profit
- Clustered Bar Chart: Sales by Category and Region
- Line Chart: Avg Profit by Category
- Slicers: Region, Month-Year
- KPIs:
  - Top Selling Category: **Eggs, Meat & Fish**
  - Most Profitable Category: **Snacks**
  - Avg Category Profit: ₹535.30K

---

## 🎯 Key Insights
- 📌 **West Region** had the highest overall sales and profit.
- 📌 **Eggs, Meat & Fish** was the top-selling category.
- 📌 **Snacks** showed the highest profit across sub-categories.
- 📌 Profit and sales peaked in Q4 across all regions.
- 📌 Discounts varied significantly by category and sub-category.

---

## 📁 Deliverables
- ✅ Dashboard PDF (`Task 8 DA.pdf`)
- ✅ Dataset CSV (if needed)
- ✅ README.md (this file)






# SuperMart-Sales-Dashboard-Task8-DA-
