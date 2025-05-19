# 📊 Sales & Customer Insights Dashboard

An interactive **Tableau dashboard** built to provide actionable insights into sales performance and customer behavior, supporting data-driven decision-making for marketing and business strategy teams.

---

## 🎯 Project Overview

This project contains two dynamic dashboards:

1. **Sales Dashboard** – Focuses on analyzing year-over-year sales metrics and identifying sales trends.  
2. **Customer Dashboard** – Helps understand customer segments, behaviors, and engagement patterns.

Both dashboards allow historical comparisons and are designed for intuitive interactivity and deep exploration.

---

## 🧰 Tools & Technologies Used

- **Tableau** – For interactive visualizations and dashboard development  
- **Microsoft Excel** – For initial data storage and preprocessing  
- **Calculated Fields** – To define KPIs and measures within Tableau  
- **Level-of-Detail (LOD) Expressions** – For complex aggregations and insights

---

## 🧾 Sales Dashboard – Features & Requirements

### 📌 Dashboard Purpose
Provide a high-level summary and in-depth breakdown of sales metrics to evaluate trends and performance across time and categories.

### 🔑 Key Features

- **KPI Overview**  
  Displays total sales, profits, and quantity for both the current and previous year.

- **Sales Trends**  
  Monthly breakdown of each KPI for current and previous year.  
  Highlights months with highest and lowest sales.

- **Product Subcategory Comparison**  
  Compare sales and profit by product subcategories across years.

- **Weekly Trends for Sales & Profit**  
  Weekly performance with average value indicators.  
  Highlights weeks above and below average performance.

---

## 👥 Customer Dashboard – Features & Requirements

### 📌 Dashboard Purpose
Offer an overview of customer engagement, order patterns, and profitability to aid customer segmentation and retention strategy.

### 🔑 Key Features

- **KPI Overview**  
  Summarizes number of customers, sales per customer, and total orders for current and previous year.

- **Customer Trends**  
  Monthly view of customer KPIs and highlights of peak/low activity months.

- **Customer Distribution by Order Count**  
  Categorizes customers based on the number of orders to analyze loyalty and engagement.

- **Top 10 Customers by Profit**  
  Ranks customers by profit, showing order count, sales, last order date, etc.

---

## 🛠️ Interactivity & Usability Features

- **Dynamic Year Selection**  
  Users can choose any year for historical data review.

- **Cross-Navigation Between Dashboards**  
  Easily toggle between Sales and Customer dashboards.

- **Chart-Driven Filtering**  
  Click on visual elements (charts, bars, maps) to drill down into specific segments.

- **Flexible Filtering Options**  
  Filter by product category/subcategory  
  Filter by region, state, and city

---

## 📂 File Structure

```
project/
├── data/
│   └── sales_data.xlsx                # Raw and processed sales/customer data
├── dashboards/
│   ├── sales_dashboard.twbx           # Tableau workbook for sales insights
│   └── customer_dashboard.twbx        # Tableau workbook for customer analysis
├── assets/
│   └── dashboard_screenshots/         # Screenshots/images for documentation
└── README.md                          # Project documentation
```
