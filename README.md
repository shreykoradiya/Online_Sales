
# 📊 E-Commerce Online Sales Dashboard

This project is an interactive Power BI dashboard designed to visualize and analyze sales data for an e-commerce business. The dashboard provides clear insights into sales, profit, quantity, customer behavior, and payment modes.

---

## 📁 **Dataset Overview**

The dataset consists of two main tables:
1. **Sales Orders Table**
   - **Columns:** Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode
   - Captures details about each order including product category, sub-category, and payment method.

2. **Customer Detail Table**
   - **Columns:** Order ID, Order Date, Customer Name, State, City
   - Contains customer names, states, cities, and the order dates.

These tables are joined via the **Order ID** column to create a relational data model.

---

## 📌 **Dashboard Highlights**

The dashboard includes the following key sections:

- **KPIs:**  
  - **Sum of Amount:** Total sales revenue (`438K`)
  - **Sum of Profit:** Total profit (`37K`)
  - **Sum of Quantity:** Total quantity sold (`5615`)

- **Visuals:**
  - **Total Sales by State:** Shows top-performing states (Maharashtra, Madhya Pradesh, Uttar Pradesh, Delhi, Rajasthan).
  - **Average Order Value (AOV) by Category:** Distribution of revenue across `Electronics (38%)`, `Clothing (34%)`, and `Furniture (28%)`.
  - **Profit - Loss by Month:** Displays monthly profit and loss trends to identify seasonal fluctuations.
  - **Sum of Amount by Customer Name:** Highlights top contributing customers.
  - **Quantity by Payment Mode:** Shows customer preference for `COD (44%)`, `UPI (21%)`, `Debit Card`, `Credit Card`, and `EMI`.
  - **Profit by Category:** Compares total profit from `Clothing`, `Electronics`, and `Furniture`.
  - **Profit by Sub-Category:** Highlights top profitable sub-categories (`Printers`, `Bookcases`, `Saree`, etc.).

- **Filter Panel:** Users can filter by `Quarter (Q1 - Q4)` for flexible time-based analysis.

---

## ✅ **Key Insights**

- **Maharashtra** is the top-performing state by sales amount.
- `COD` is the most popular payment mode.
- `Electronics` contributes the highest share in Average Order Value.
- Certain sub-categories like `Printers` and `Bookcases` yield significant profit.
- Monthly trends show fluctuations with occasional losses (e.g., May, June).

---

## ⚙️ **How to Use**

1. **Load the Data:** Use the provided CSV/Excel files for the sales and customer datasets.
2. **Connect & Model:** Join both tables on the `Order ID` field.
3. **Build Visuals:** Create visuals as shown, using appropriate charts (bar, donut, line).
4. **Apply Filters:** Add quarter or month filters for detailed analysis.
5. **Analyze:** Use the dashboard to monitor KPIs, trends, and customer/payment patterns.

---

## 📈 **Tools Used**

- **Power BI Desktop**
- Relational Data Model
- DAX Measures for KPIs and calculated fields

---

## 🚀 **Next Steps**

- Add drill-through pages for customer or product-level deep dives.
- Automate data refresh for real-time insights.
- Expand with more dimensions like marketing channel or delivery time.

---

## 📃 **Author**

**Project by:** *Shrey Koradiya*  

