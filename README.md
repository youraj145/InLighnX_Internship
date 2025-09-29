# 📊 E-commerce Sales Performance Dashboard (Data Analyst Internship Project)

## Project Overview
This Power BI dashboard was developed during my **Data Analyst Intern program at InLighnX Global Pvt. Ltd.**, running from **July 2025 to October 2025**.  

The goal was to transform raw transactional and customer data into an **intuitive, interactive dashboard** that allows stakeholders (e.g., Sales Managers, Marketing Teams) to:
- Monitor key business metrics  
- Identify profitable customer segments  
- Analyze product category performance  

---

## 🔑 Key Performance Indicators (KPIs) Monitored
The dashboard tracks the health of the e-commerce business using the following calculated metrics:

| **KPI**              | **Description**                                   | **Insight Provided**                                   |
|-----------------------|---------------------------------------------------|-------------------------------------------------------|
| **Total Amount**      | Total revenue generated from all orders.          | Overall sales magnitude.                              |
| **Total Profit**      | Gross profit after subtracting costs.             | Business health and profitability trends.             |
| **Total Quantity**    | Total number of units sold.                       | Inventory and supply chain demand.                    |
| **Average Order Value (AOV)** | Total Amount ÷ Total Orders.                | Customer spending behavior & marketing effectiveness. |

---

## 📂 Data Sources and Transformation

### 1. Data Sources
- **Orders.csv** → Contains high-level order information (Order ID, Order Date, Customer Name, State, City).  
- **Details.csv** → Contains line-item details (Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode).  

### 2. Data Modeling & DAX
- **One-to-Many Relationship** → Orders (1) ↔ Details (Many) via *Order ID*.  
- **DAX Calculations** included:  
  - Time Intelligence: *Year-over-Year Growth*, *Quarterly Trends*  
  - Custom Measures: *Profit Margin*, *Average Order Value (AOV)*  

---

## 📊 Dashboard Insights

- **Geographic Performance** → Map visualization showing sales & profit by state (e.g., Maharashtra, Uttar Pradesh as top regions).  
- **Product Deep Dive** → Category & Sub-Category analysis (e.g., Clothing dominant, Printers high-profit, Saree low-profit).  
- **Customer Behavior** → Top customers ranked by sales & profit contribution.  
- **Payment Analysis** → COD vs UPI vs Credit Card sales breakdown.  
- **Time Series Analysis** → Monthly/Quarterly sales & profit trends for forecasting.  

---

## 📁 Repository Contents
- `Ecommerce Sales Dashboard.pbix` → Power BI file (data model, DAX, visuals).  
- `Orders.csv` → Order metadata.  
- `Details.csv` → Transactional line-item details.  
- `Ecommerce Sales Dashboard.pdf` → Exported dashboard snapshot for quick view.  

---

## 🖼️ Preview
*(Update the path after uploading actual image)*  

![Dashboard Screenshot](https://github.com/youraj145/InLighnX_Internship/blob/main/IMG.png)

---

## ⚙️ How to Use
1. **Prerequisite** → Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).  
2. **Download** → Clone this repository or download the files.  
3. **Open** → Load `Ecommerce Sales Dashboard.pbix` in Power BI Desktop.  
4. **Explore** → Interact with slicers/filters (Quarter, Month, Payment Mode) to explore business insights.  

---

## 📌 Internship Info
- **Company**: InLighnX Global Pvt. Ltd.  
- **Role**: Data Analyst Intern  
- **Duration**: July 2025 – October 2025  

---
✅ *This project demonstrates real-world data analysis using Power BI, transforming raw e-commerce data into actionable insights for decision-makers.*
