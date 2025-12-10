# 🔥 Steel Sales Performance Dashboard  
*Powered by Power BI & Power Query*

---

## 1. Project Overview  
This project analyzes the sales performance of a steel manufacturing company to help understand revenue trends, product success, category changes, and customer buying patterns. The goal is to equip decision-makers with clear, data-driven insights.

---

## 2. Dataset Summary  
The dataset includes:  
- Customer details (ID, Type)  
- Product details (Category, Name)  
- Region details (Region Name)  
- Sales transactions (Quantity, Unit Price, Sales Amount, Order Date)  
- Date information for time analysis  

Data cleaning and transformation were done using **Power Query**. The dashboard was built in **Power BI**.

---

## 3. Data Model  
A star schema was designed to keep the data organized and analysis efficient:  
- **FactSales** (central sales data)  
- Dimension tables:  
  - `DimCustomer`  
  - `DimProduct`  
  - `DimRegion`  
  - `DateTable`  

This structure enables smooth filtering and slicing of data.

**Data Model Screenshot:**  
![View Data Model](https://github.com/Subham-Adhikari/steel-sales-performance-dashboard/blob/main/Dashboard%20%26%20Data-Model/data_model_.png)

---

## 4. Dashboard Highlights  

### 📊 Overall KPIs  
- 💰 **Total Revenue:** 10M  
- 🛒 **Total Orders:** 891  
- 👥 **Total Customers:** 200  

### 📈 Monthly Sales Trend  
Shows sales variation month-to-month to identify peaks and dips.

### 🏆 Top 5 Products  
Highlights the highest revenue-generating products for focused strategy.

### 🔄 Category Rank Movement  
Tracks ranking changes of product categories (Steel, Alloys, Refractory) over quarters.

### 📉 Refractory Sales Drop (Q3 → Q4)  
Waterfall chart explaining the significant sales decline in Q4 for Refractory products.

**Dashboard Image:**  
![View Dashboard](https://github.com/Subham-Adhikari/steel-sales-performance-dashboard/blob/main/Dashboard%20%26%20Data-Model/dashboard_.png)

---

## 5. Key Business Findings  
- Steel category leads in revenue generation.  
- Refractory category sales peak in Q3 but drop sharply in Q4.  
- Sales heavily rely on a few top products.  
- Monthly sales fluctuate, pointing to potential inventory and forecasting challenges.

---

## 6. Recommendations  
- 🔍 Investigate causes of the Q4 Refractory sales drop (operational or market-driven)  
- 📢 Strengthen marketing & inventory for best-performing products  
- 💡 Explore ways to boost lower-performing categories  
- 📅 Use monthly sales trends for better demand forecasting and inventory planning

---

## 7. Tools Used  
- **Power BI:** Dashboard visualization, data modeling, and calculations  
- **Power Query:** Data cleansing and preparation  

---

## 8. How to Use This Report  
- Download the `.pbix` file from the repository  
- Open with Power BI Desktop  
- Use slicers/filters for detailed exploration  
- Adjust date ranges to analyze different time periods  

---
