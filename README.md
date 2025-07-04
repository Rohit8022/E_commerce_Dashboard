# 🛒 Ecom Insights: Global E-Commerce Sales Dashboard

An interactive, visually intuitive Power BI dashboard designed to explore and analyze global e-commerce sales performance, customer behavior, regional trends, and product category performance across multiple dimensions.

---

## 📌 Short Description / Purpose

The Ecom Insights Dashboard provides stakeholders—such as sales managers, marketing teams, and data strategists—with actionable insights into sales performance across regions, time periods, and product categories. The dashboard simplifies decision-making by highlighting sales KPIs, customer segmentation, revenue growth trends, and high-performing product categories.

---

## 🛠️ Tech Stack

This dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Primary platform for report creation and data visualization.  
- 🔄 **Power Query** – Used to clean, transform, and model the sales data.  
- 🧠 **DAX (Data Analysis Expressions)** – Applied to create custom measures like YOY growth, average order value, and customer retention.  
- 🧩 **Data Modeling** – Relationships set up between tables (Orders, Products, Customers, Regions, Date) to allow seamless cross-filtering and aggregation.  
- 📁 **File Format** – `.pbix` for development and `.png` or `.jpg` for visual preview.

---

## 📂 Data Source

- **Source:** Synthesized retail e-commerce data from open datasets and simulated transactions.
- **Dataset Description:**
  - Orders table: Sales transactions with fields like Order ID, Customer ID, Product, Quantity, Order Date, Revenue.
  - Products table: Product details like Category, Subcategory, Cost Price, and Selling Price.
  - Customer table: Customer demographics, acquisition channel, and repeat purchase flag.
  - Regions table: Geographic info (Country, State, City).
  - Date table: Time intelligence features (Year, Month, Week, Quarter).

---

## ✨ Features / Highlights

### • Business Problem

E-commerce companies often struggle with fragmented data across platforms, making it difficult to identify top-performing products, understand customer behavior, or optimize marketing spend in real time.

### • Goal of the Dashboard

To create a centralized, interactive visual analytics tool that:

- Provides a 360-degree view of e-commerce sales metrics.
- Empowers teams to track and optimize performance by region, time, and category.
- Enables quick identification of sales trends, customer segments, and growth opportunities.

### • Walkthrough of Key Visuals

- **KPI Panel (Top Left)**  
  Displays critical sales metrics including:  
  - Total Revenue  
  - Total Orders  
  - Average Order Value (AOV)  
  - Customer Retention Rate  
  - Top-Selling Product  
  - Repeat vs New Customers

- **Sales by Region (Choropleth Map)**  
  Interactive map showing revenue distribution by country/region.

- **Sales Trends Over Time (Line Chart)**  
  Tracks monthly sales and order trends. Useful for seasonal analysis and growth tracking.

- **Product Category Performance (Stacked Column Chart)**  
  Breaks down revenue by category and subcategory over time.

- **Customer Segmentation (Donut Chart + Matrix)**  
  Shows segmentation by acquisition source, repeat customers, and demographics.

- **Profitability Analysis (Bar Chart)**  
  Visualizes profit margins per category or product.

- **YOY and MOM Growth Cards**  
  Highlight percentage change in revenue and orders for Year-over-Year and Month-over-Month comparisons.

### • Business Impact & Insights

- 📈 **Sales Strategy Optimization:** Helps sales teams identify high-performing regions and low-performing categories.
- 🎯 **Targeted Marketing:** Marketing teams can use customer insights to launch more effective campaigns.
- 🔍 **Product Performance Tracking:** Identify top/bottom sellers and optimize inventory.
- 📊 **Executive Reporting:** Provides a clean and professional interface for decision-makers.

---

## 🖼️ Screenshots / Demos

Add screenshots by placing image files (e.g., `dashboard_main.png`, `category_analysis.png`) in a folder named `/assets` and then embed them like this:

```markdown
### 🧭 Main Dashboard Overview  
![Main Dashboard](./dashboard.png)

### 🛍️ Category-Level Sales Breakdown  
![Category Breakdown](./assets/category_analysis.png)

### 🌍 Regional Revenue Map  
![Regional Map](./assets/revenue_map.png)
