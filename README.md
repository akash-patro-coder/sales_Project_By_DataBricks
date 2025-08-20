# sales_Project_By_DataBricks

# 📊 Sales Data SQL Project

This repo contains a sample **sales dataset** and SQL queries to analyze it in **Databricks SQL**.

---

## 🔑 Table Schema
```sql
CREATE TABLE sales (
  sale_id BIGINT GENERATED ALWAYS AS IDENTITY,
  region STRING,
  product STRING,
  quantity INT,
  amount DECIMAL(10,2),
  sale_date DATE,
  customer_name STRING
);


📌 Key Queries

Total sales per region

Orders placed on/after a given date

Customers with purchases > ₹1000

Top-spending customers (cumulative)

Highest single sale and its region
