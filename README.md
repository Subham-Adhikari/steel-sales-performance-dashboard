# Steel Sales Performance Dashboard  
**Power BI + Power Query**

## 1. Project Overview  
This project analyzes the sales performance of a steel manufacturing company.  
The goal is to understand revenue trends, product performance, category movement, and customer activity.  
The dashboard enables stakeholders to make clear, data-driven decisions based on sales insights.

---

## 2. Dataset Summary  
The dataset includes information about customers, products, regions, sales transactions, and a date table.  
Data cleaning, transformation, and preparation were performed using **Power Query**, and the dashboard was developed in **Power BI**.

### Key Data Fields:
- Customer details (Customer ID, Customer Type)  
- Product details (Category, Product Name)  
- Region details (Region Name)  
- Date fields for time intelligence  
- Sales transaction data (Quantity, Unit Price, Sales Amount, Order Date)

---

## 3. Data Model  
A **Star Schema** was designed for efficient analytics.

- **FactSales** (central fact table)  
- Connected dimension tables:  
  - `DimCustomer`  
  - `DimProduct`  
  - `DimRegion`  
  - `DateTable`  

This model supports accurate filtering, segmentation, and time-series analysis.

*(Data model image displayed above in repository)*

---

## 4. Dashboard Insights  

### **Overall KPIs**
- **Total Revenue:** 10M  
- **Total Orders:** 891  
- **Total Customers:** 200  

Provides a quick snapshot of company performance.

### **Monthly Sales Trend**
Shows how sales change month by month and helps identify high and low-performing periods.

### **Top 5 Products**
Displays the highest revenue-generating products for better product strategy and inventory management.

### **Category Rank Movement**
Shows how each product category (Steel, Alloys, Refractory) performs across quarters and how rankings shift.

### **Total Sales by Category**
Breakdown of revenue contribution by each category.

### **Average Sales by Category**
Shows which category has the highest average revenue per order.

### **Refractory Sales Drop (Q3 → Q4)**
A waterfall chart explains the reasons behind the significant drop in refractory sales during Q4.

*(Dashboard image also included above in repository)*

---

## 5. Key Business Findings  
- Steel category generates the highest revenue overall.  
- Refractory category performs well in Q3 but drops significantly in Q4.  
- Sales depend heavily on a small number of top products.  
- Monthly sales fluctuate, indicating potential forecasting and inventory challenges.

---

## 6. Recommendations  
- Investigate the Q4 drop in Refractory sales and address operational or demand-side issues.  
- Strengthen marketing and production planning for top-performing products.  
- Explore opportunities to improve lower-performing categories.  
- Use monthly trend analysis for better inventory and demand forecasting.

---

## 7. Tools Used  
- **Power BI:** Data modeling, DAX calculations, and dashboard development  
- **Power Query:** Data cleaning, shaping, and processing  

---

## 8. How to Use This Report  
- Download the `.pbix` file from the repository  
- Open it using Power BI Desktop  
- Use slicers and filters for deeper exploration  
- Adjust date range to analyze different time periods  

---

