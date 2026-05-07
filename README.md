# 🛒 Olist Store Analysis Dashboard (Excel Project)

## 📌 Project Overview
This project is based on the Brazilian E-Commerce dataset **Olist Store Analysis**.  
The objective of this project is to analyze customer behavior, sales performance, delivery performance, payment trends, and review ratings using **Microsoft Excel Dashboarding techniques**.

The dashboard was created using:
- Excel Power Query
- Power Pivot (Data Modeling)
- Pivot Tables
- Pivot Charts
- DAX Measures
- Interactive Slicers

---

# 📂 Dataset Information

### Domain:
E-Commerce

### Dataset Used:
Olist Store Dataset (2017–2018)

### Total Files:
9 CSV Files

### Main Tables:
- Customers
- Orders
- Order Items
- Order Payments
- Order Reviews
- Products
- Sellers
- Geolocation
- Product Category Translation

---

# 🧹 Data Cleaning & Transformation

The following data cleaning steps were performed:

- Removed null and invalid records
- Converted timestamp columns into proper date format
- Created calculated columns for:
  - Delivery Days
  - Weekday vs Weekend Orders
- Handled incorrect delivery dates
- Built relationships between multiple tables using Power Pivot

---

# 🔗 Data Modeling

Relationships were created between:
- Orders ↔ Customers
- Orders ↔ Payments
- Orders ↔ Reviews
- Orders ↔ Order Items
- Products ↔ Order Items
- Product Translation ↔ Products

A proper star-schema style model was implemented for analysis.

---

# 📊 KPI Metrics Used

The dashboard includes the following KPIs:

- Total Orders
- Total Revenue
- Average Rating
- Average Delivery Days

---

# 📈 Dashboard Insights

The dashboard provides insights on:

### ✔ Weekday vs Weekend Sales Analysis
Comparison of revenue generated during weekdays and weekends.

### ✔ Order Status Breakdown
Analysis of delivered, shipped, and canceled orders.

### ✔ Monthly Revenue Trend
Monthly sales trend analysis for business growth tracking.

### ✔ Sao Paulo Customer Analysis
Average product price and payment analysis for Sao Paulo customers.

### ✔ Delivery Performance Analysis
Average delivery time and customer review relationship analysis.

---

# 🛠 Tools & Technologies Used

- Microsoft Excel
- Power Query
- Power Pivot
- DAX
- Pivot Tables
- Pivot Charts
- Slicers

---

# 🎯 Key Learnings

Through this project, I learned:
- Data Cleaning in Excel
- Data Modeling using Power Pivot
- DAX Calculations
- Dashboard Design
- Business KPI Analysis
- Interactive Reporting

---

# 📸 Dashboard Preview
<img width="1456" height="678" alt="Screenshot (82)" src="https://github.com/user-attachments/assets/f72dc481-60cf-4791-bf46-707026e8b0af" />



---

# 🚀 Future Improvements

- Power BI Version
- Dynamic Drill-through Analysis
- Advanced DAX Measures
- Customer Segmentation Analysis

