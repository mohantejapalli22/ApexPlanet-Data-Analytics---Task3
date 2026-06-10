# Task 3: Deep-Dive Sales Analysis & Interactive Dashboarding

##  Objective
Perform a detailed analysis of sales data using Python and Power BI.  
The goal is to calculate KPIs, explore regional and category performance, and build interactive dashboards for business insights.

---

## Dataset
- **File:** `sales.csv`
- **Columns:** OrderID, OrderDate, Product, Category, Region, Sales, Profit

---

##  Python Analysis (`analysis.py`)
Steps performed:
1. **Load dataset** using Pandas.
2. **Calculate KPIs**:
   - Total Sales
   - Total Profit
   - Total Orders
   - Average Sales per Order
3. **Group analysis**:
   - Region-wise Sales
   - Category-wise Profit
   - Top Products by Sales
4. **Visualizations**:
   - Bar chart → Region Wise Sales
   - Pie chart → Category Wise Profit
   - Bar chart → Product Wise Sales

 This script validates the dataset and provides static charts for initial exploration.

---

##  Power BI Dashboards
Two interactive dashboards were created:

### Page 1 – Sales & Profit Performance
- KPI Cards (Sales, Profit, Orders, Avg Sales/Order)
- Category-wise Sales (Pie Chart)
- Region-wise Profit (Bar Chart)
- Monthly Sales Trend
- Top Products by Sales
- Filters: Category, Region, Date

**Key Insights:**
- Technology category dominates sales (43%).
- East region leads profit (39K).
- February peak, June dip in sales.
- Laptop is the top product (105K).

---

### Page 2 – Sales & Profit Deep Dive
- Profit Margin by Category
- Monthly Sales Trend (Jan–Jun)
- Profit vs Sales Scatter Plot
- Region vs Category Matrix
- Monthly Category Sales (Bar Chart)

**Key Insights:**
- Technology products dominate revenue.
- Strong correlation between sales and profit.
- East region consistently outperforms others.
- Seasonal variation observed across months.

---

##  Interactive Features
- Dynamic slicers (Category, Region, Date)
- Cross-filtering between visuals
- Drill-down analysis
- Real-time KPI updates

---

##  Business Takeaways
- Prioritize Technology category for growth.
- Replicate East region’s successful practices.
- Broaden product portfolio to reduce concentration risk.
- Monitor seasonal dips (e.g., June) with targeted campaigns.

---

##  Deliverables
- `sales.csv` → Dataset  
- `analysis.py` → Python analysis script  
- `PowerBI_Dashboard.pbix` → Interactive dashboard file  
- `README.md` → Documentation  
- `/images` → Dashboard screenshots (Page 1 & Page 2)

---
