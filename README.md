# Customer_Behavior_Analysis

## 📌 Project Overview
This project analyzes **customer shopping behavior** using transactional data from **3,900 purchases** across multiple product categories. The objective is to uncover actionable insights into **spending patterns, customer segments, product preferences, discounts, and subscription behavior** to support data-driven business decisions.

---

## 📊 Dataset Summary
- **Total Records:** 3,900
- **Total Columns:** 18
- **Data Type:** Transactional customer purchase data

### Key Features
- **Customer Demographics:** Age, Gender, Location, Subscription Status
- **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color
- **Shopping Behavior:** Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type
- **Missing Values:** 37 null values in the `Review Rating` column

---

## 🧹 Exploratory Data Analysis (Python)
EDA and data preprocessing were performed using **Python (pandas)**.

### Steps Performed
- Data loading and initial exploration
- Missing value imputation using median rating per product category
- Column standardization (snake_case)
- Feature engineering (age groups, purchase frequency)
- Data consistency checks
- Loaded cleaned data into PostgreSQL

---

## 🧮 Data Analysis Using SQL (MySQL)
Key business-focused analyses:
1. Revenue by gender
2. High-spending discount users
3. Top 5 products by rating
4. Shipping type comparison
5. Subscribers vs non-subscribers
6. Discount-dependent products
7. Customer segmentation
8. Top 3 products per category
9. Repeat buyers & subscriptions
10. Revenue by age group

---

## 📈 Power BI Dashboard
An interactive Power BI dashboard was created to visualize KPIs, trends, product performance, subscription impact, and customer segments.

---

## 💡 Business Recommendations
- Boost subscriptions with exclusive benefits
- Implement customer loyalty programs
- Optimize discount strategies
- Highlight top-rated and best-selling products
- Focus marketing on high-value customer segments

---

## 🛠️ Tools & Technologies
- Python (pandas)
- MySQL
- Power BI

---

## 📎 Conclusion
This project demonstrates an end-to-end data analytics workflow using Python, SQL, and Power BI to derive meaningful business insights from customer shopping data.
