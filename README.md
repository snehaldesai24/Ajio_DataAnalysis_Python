# 🛒 Ajio Data Analysis Using Python

## 📌 Overview

This project presents an end-to-end **Exploratory Data Analysis (EDA)** on Ajio's transaction and customer order data to identify key business trends, customer behavior, product performance, and promotional effectiveness.

Ajio is one of India’s top fashion e-commerce platforms. Through a simulated/representative dataset, this project uncovers strategic insights to support Ajio's marketing, operations, and product teams in making data-driven decisions.

---

## 🎯 Project Goals

- Analyze customer behavior across orders and transactions  
- Understand coupon and reward program effectiveness  
- Identify top-performing products  
- Determine preferred transaction modes  
- Discover time-based shopping patterns  
- Combine multiple visuals into a dashboard for storytelling  

---

## 📈 Analysis Workflow

### 1️⃣ Data Cleaning & Transformation

- Combined multiple datasets using common keys
- Parsed and standardized datetime columns
- Created derived features:
  - `Hour` from `Order_Time`
  - `Coupon_Used` (binary flag)
  - `Reward_Flag` (binary flag)

---

### 2️⃣ Exploratory Data Analysis (EDA)

#### ✅ Coupon & Discount Usage
- Percentage of orders using coupons
- Comparison of average discount with vs without coupons
- Impact of discounts on reward eligibility

#### ✅ Reward Program Evaluation
- Products with highest reward redemption
- Customers most likely to earn rewards
- Reward usage trends by hour and transaction mode

#### ✅ Product-Level Trends
- Top 10 most ordered products
- Products contributing most to reward issuance
- Quantity trends across products

#### ✅ Time-of-Day Patterns
- Hourly order frequency (0–23)
- Coupon and reward usage by hour
- Identification of peak shopping hours

#### ✅ Transaction Mode Breakdown
- Distribution of payment methods (UPI, Wallet, Card, etc.)
- Coupon and reward usage by payment mode
- Time-based transaction preferences

---

## 🛠️ Tools & Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)    
- Jupyter Notebook  
- CSV files  

---

## ✅ Conclusion

This project demonstrates the effectiveness of exploratory data analysis in revealing actionable insights for a fashion e-commerce platform. It helps identify opportunities for optimization in customer engagement, promotional strategy, and operational efficiency through data storytelling.
