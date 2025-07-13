# 📊 E-commerce Customer Churn Analysis
**Author:** Arshita Chatha  
**Tech Stack:** PostgreSQL, Power BI, pgAdmin 4, SQL  

## 🧠 Project Overview
This project analyzes customer churn behavior in an e-commerce setting. The goal is to understand patterns and key drivers behind customer churn using SQL for data exploration and Power BI for dashboard visualization.

---

## 📁 Dataset Details

- **Source:** The dataset used was originally sourced from an open e-commerce churn dataset.
- **Format:** The data was loaded into PostgreSQL using `.sql` insert statements (~5630 records).
- **Table Name:** `ecommerce_churn`
- **Key Columns:**
  - `CustomerID`
  - `Tenure`
  - `PreferredLoginDevice`
  - `CityTier`
  - `Churn` (binary target variable)
  - `SatisfactionScore`
  - `WarehouseToHome`, `OrderCount`, `DaySinceLastOrder`, etc.

---

## ⚙️ Project Setup

### 1. Setup PostgreSQL & pgAdmin
- Install **PostgreSQL** and **pgAdmin 4**
- Create a new database: `churn analysis project`
- Run the provided SQL insert script to populate the `ecommerce_churn` table.

### 2. Execute SQL Queries
Use pgAdmin to run the analysis queries such as:
- Churn rate by payment method
- Impact of login device, city tier, satisfaction score
- Average orders and session time for churned vs. retained users
- Overall churn rate: **16.84%**

### 3. Visualize in Power BI
Power BI was used to build an executive dashboard showing:
- Total customers
- Churn rate
- Churn by segment (device, city, tenure, etc.)
- Actionable insights with charts and KPIs

📷 **Dashboard Screenshot:**
![Churn Dashboard]("C:\Users\Dell\Downloads\E-commerce Customer Churn Dashboard.png")

---

## 📊 Key Insights from Analysis

- 🔹 **Churn Rate:** 16.84%
- 🔹 **Most churned customers:**
  - Were **male (63.29%)**
  - Were **single (50.63%)**
  - Used **mobile phones to log in**
  - Lived in **Tier 2 and Tier 3 cities**
  - Had a **satisfaction score of 5**
  - Registered a **complaint**
- 🔹 Short-tenure customers and those with **more devices** churned more.
- 🔹 Highest churn by **payment method:** Cash on Delivery and E-wallet

---

## 📌 Skills Demonstrated

- Advanced SQL querying & aggregations
- EDA on relational data using PostgreSQL
- Data visualization and dashboard design in Power BI
- Analytical storytelling and insight generation

---

## 🧾 Files in Repository
- `ecommerce_churn_insert.sql` – SQL data insert script
- `churn_analysis_queries.sql` – SQL analysis queries
- `A_dashboard_titled_"Arshita_Chatha_E-commerce_Cust.png` – Power BI dashboard image
- `README.md` – Project documentation

---

## 📇 Contact
**Arshita Chatha**  
Connect with me for collaborations or insights on data analytics projects!
