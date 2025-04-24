
---

## 📊 Sales Insights Dashboard – Superstore Dataset

### 🔗 [🔎 View Power BI Dashboard](#) | [💻 Source File (`.pbix`)](./SuperStore%20-%20Bi%20Dashboard.pbix)
### 🔗 [Raw Data (Excel)](#) | [💻 Source File (`.xlsx`)](./Sample%20-%20Superstore.xlsx)**
---

### 🌟 Project Overview

This project explores sales data from a fictional superstore and delivers **actionable insights** through a dynamic Power BI dashboard. Designed with business decision-making in mind, the dashboard enables users to slice and drill into data across various dimensions such as region, product, category, time, and customer behavior.

---

### 🌐 Objective

To build an **interactive, self-service dashboard** that helps stakeholders answer:

- Which products are top-sellers?
- How is performance trending over time?
- What regions are under/overperforming?
- Are we meeting our sales targets?

---

### ⭐️ Data Model – Star Schema

The dashboard is structured using a **star schema** for optimal performance and clarity:

- **Fact Table**: `Orders`
  - Measures: Sales, Profit, Quantity
  - Keys: Order ID, Product ID
- **Dimension Tables**:
  - `Products`: Product Name, Category, Sub-Category
  - `Customers`: Customer Name, Segment, City
  - `Dates`: Date, Month, Year, Quarter
  - `Returns`: Order ID, Returned (Yes/No)

---

### 📈 Key Visuals & Features

| Visual Type           | Description |
|------------------------|-------------|
| 📉 **Sales Trend Over Time** | Line chart comparing current vs. last year's sales |
| 🌍 **Regional Sales Bar Chart** | Clustered bars showing region-wise sales, color-coded |
| 🏆 **Top 10 Products** | Bar chart sorted by total sales |
| 🧭 **KPIs** | Total Sales, Profit, Quantity, and Target vs. Actual |
| 🧩 **Slicers** | Interactive filters by Date, Region, Category, Sub-Category |
| 🔎 **Drill-Through** | Detailed transaction-level page (Order ID, City, Product, etc.) |

---

### 🔔 Advanced Functionality

- ✅ **Drill-Through Navigation**: Right-click on any region or product to view order-level details.
- 🧮 **Calculated Columns**: Month name, Month-Year, and Target-based performance tags.

---

### 💡 Business Insights

- **Central and West regions** outperformed East and South.
- Categories like **Technology** and **Office Supplies** drove the most revenue.
- A small number of products contribute a **large portion of sales** (Pareto 80/20).
- Some **high-return items** negatively impact profitability.

---

### 🛠 Tools & Tech

- **Power BI Desktop**
- Excel (Data Cleansing)
- DAX for Measures and KPIs

---

### 🧠 Learnings

This project enhanced my skills in:

- Data modeling using Star Schema
- DAX calculations for dynamic KPIs
- User-focused design for intuitive dashboards

---
