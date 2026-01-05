

# 🛒 Superstore Sales & Profit Analysis (EDA)

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on the Superstore dataset to uncover insights related to **sales performance, profitability, customer behavior, time trends, and discount impact**.
The goal is to understand **what drives revenue, what hurts profit, and where business decisions can be improved** using data.

---

## 🎯 Objectives

* Analyze overall sales, profit, and quantity trends
* Identify high-performing and low-performing categories & sub-categories
* Understand customer purchasing and profitability behavior
* Examine seasonal and time-based trends
* Evaluate the **impact of discounts on profitability**
* Provide **actionable business insights and recommendations**

---

## 🧰 Tools & Libraries Used

* **Python**
* **Pandas** – data manipulation & aggregation
* **NumPy** – numerical operations
* **Matplotlib** – data visualization
* **Jupyter Notebook** – analysis environment

---

## 📂 Dataset Description

The dataset contains retail transaction data including:

* Order & shipping details
* Product categories and sub-categories
* Sales, profit, quantity, and discounts
* Customer and regional information

**Rows:** ~9,994
**Columns:** 21

---

## 🔎 Project Phases & Key Insights

---

### 🔹 Phase 1: Data Overview

* Verified dataset structure, shape, and data types
* Converted date columns to proper datetime format
* No missing values or duplicate records found

**Insight:**
The dataset is clean and reliable, allowing confident analysis without heavy preprocessing.

---

### 🔹 Phase 2: Data Cleaning & Feature Engineering

* Created new features:

  * `Order_Year`, `Order_Month`
  * `Year-Month`
  * `Shipping_Days`
* Prepared data for time-based and performance analysis

**Insight:**
Feature engineering enabled deeper insights into seasonality and delivery patterns.

---

### 🔹 Phase 3: Sales Performance Analysis

* Analyzed sales & profit by:

  * Category
  * Sub-Category
  * Segment
  * Region
  * Product

**Key Insights:**

* **Technology** and **Office Supplies** generate the highest profit
* **Furniture** shows strong sales but weaker profitability
* Some products have **high sales but low profit**, indicating inefficiencies

---

### 🔹 Phase 4: Time-Based Analysis

* Studied trends by:

  * Year
  * Month
  * Year-Month

**Key Insights:**

* Sales show an **overall upward trend over time**
* Seasonal patterns exist, with peak sales in specific months
* Profit growth is less stable, suggesting margin pressure

---

### 🔹 Phase 5: Customer Analysis

* Identified:

  * Top customers by sales and profit
  * Repeat vs one-time customers
  * Average Order Value (AOV)
* Segmented customers based on sales & profit contribution

**Key Insights:**

* High-spending customers are not always the most profitable
* Repeat customers generally provide better value
* Some customers generate volume through heavy discounting

---

### 🔹 Phase 6: Discount & Profitability Analysis

* Categorized discounts into:

  * No, Low, Medium, High
* Studied discount impact by:

  * Profit
  * Category
  * Sub-Category

**Key Insights:**

* Higher discounts strongly correlate with **lower average profit**
* Several sub-categories show:

  * High sales
  * High discounts
  * Low or negative profit
    → These are **problem areas**

---

## 📌 Final Business Insights

* High sales do **not** always translate into high profit
* Excessive discounting erodes margins significantly
* Certain sub-categories rely on discounts to drive sales but remain unprofitable
* Customer profitability varies widely — segmentation is essential
* Seasonality can be leveraged for better planning and promotions

---

## 💡 Business Recommendations

* Re-evaluate discount strategies for low-profit sub-categories
* Focus promotions on **high-margin products**, not just high-volume ones
* Strengthen loyalty programs for high-profit repeat customers
* Adjust pricing or cost structure in underperforming categories (e.g., Furniture)
* Use seasonal trends to optimize inventory and marketing campaigns

---

## 📁 Project Structure

```
Superstore Dataset.ipynb   # Complete EDA notebook
README.md                 # Project summary and insights
```

---

## 🚀 Conclusion

This EDA project demonstrates how data can be used to:

* Identify profitability issues
* Optimize discount strategies
* Improve customer and category-level decision-making

The analysis provides a strong foundation for **further predictive modeling or business optimization tasks**.

---

## 📬 Author

**Haroon Khan**
Aspiring Data Analyst / Data Scientist
📍 Pakistan

