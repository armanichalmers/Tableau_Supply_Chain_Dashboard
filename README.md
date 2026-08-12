# 📦 Supply Chain Performance Dashboard

## 📌 Project Overview

This project was completed as part of a **Tableau Dashboard Workshop** focused on developing interactive dashboards and strengthening Tableau data visualization skills.

Using supply chain and order data, I developed an interactive Tableau dashboard that provides a consolidated view of order activity, revenue, shipping methods, and carrier performance.

---

## 📊 Interactive Tableau Dashboard

I developed an interactive **Supply Chain Performance Dashboard in Tableau** to provide a consolidated view of order value, order volume, shipping methods, and carrier performance.

The dashboard includes:

- **Average Order Value** — summarizes the average revenue generated per order.
- **Total Order Volume** — displays the total number of unique orders.
- **Average Order Value by Month** — tracks changes in average order value throughout the year.
- **Order Revenue by Shipping Method** — shows the distribution of order revenue across shipping methods.
- **Order Volume by Carrier** — compares order volume across carriers.
- **Order Year Filter** — allows users to interactively filter dashboard results by year.
- **Warehouse Code Filter** — allows users to filter the dashboard by warehouse code and compare performance across individual warehouse locations.


<p align="center">
  <a href="https://public.tableau.com/views/eXcelerate_Supply_Chain_AC/SupplyChainDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">
    <img width="800"
         alt="Supply Chain Performance Tableau Dashboard"
         src="https://github.com/user-attachments/assets/54549eff-8f58-406b-8757-4672b6071c9c" />
  </a>
</p>

<p align="center">
  <em>Click the dashboard image to explore the interactive Tableau dashboard.</em>
</p>

🔗 **[View the Interactive Tableau Dashboard](https://public.tableau.com/views/eXcelerate_Supply_Chain_AC/SupplyChainDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**


---


## 🛠️ Tools & Skills

- **Tableau**
- Dashboard Development
- Data Visualization
- Calculated Fields
- KPI Development
- Interactive Filters
- Data Aggregation
- Dashboard Formatting & Design

---

## 📁 Dataset

The Tableau dashboard was developed using the **F_ORD_Sales.csv** dataset, which contains **6,219 sales and order records across 16 fields**.

The dataset includes information related to:

- Order IDs and order dates
- Customers, products, and suppliers
- Warehouse codes
- Shipping states and shipping methods
- Carriers and order status
- Unit quantities and weights
- Unit prices and discounts
- Freight costs
- Line-level sales totals

These fields were used to develop the dashboard's KPIs, calculated fields, visualizations, and interactive filters.

📄 **[View the Supply Chain Dataset](https://github.com/armanichalmers/Tableau_Supply_Chain_Dashboard/blob/main/F_ORD_Sales.csv)**

---


## 🧮 Tableau Calculations

Calculated fields were used to create key dashboard metrics.

### Average Order Value

```text
SUM([Order_Total]) / COUNTD([Order_Number])
```

### Total Order Volume

```text
COUNTD([Order_Number])
```

---


## 🎓 Project Background

This project was completed as part of a **Tableau Dashboard Workshop** and was designed to provide hands-on experience developing an interactive business dashboard.

The project demonstrates skills in **calculated fields, KPI development, interactive filtering, data visualization, dashboard formatting, and business-focused dashboard design**.
