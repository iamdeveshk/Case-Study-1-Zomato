# 🍽️ Zomato SQL Case Study

## 📌 Overview
This project analyzes a **Zomato-style food delivery database** using SQL to derive **actionable business insights** related to user behavior, restaurant performance, revenue trends, and delivery partner earnings.

The case study focuses on using SQL as an **analytical tool** rather than just a querying language.

---

## 🛠 Tools & Skills
- SQL (MySQL)
- Multi-table JOINs
- Aggregations (`SUM`, `AVG`, `COUNT`)
- `GROUP BY` & `HAVING`
- Date functions
- NULL handling
- Business-oriented analysis

---

## 📁 Dataset Structure
The database consists of **7 interconnected tables**:

| Table Name          | Description |
|---------------------|-------------|
| `users`             | User / customer information |
| `orders`            | Order-level transaction data |
| `order_details`     | Line-item details per order |
| `restaurants`       | Restaurant metadata |
| `menu`              | Restaurant-wise menu mapping |
| `food`              | Food item catalog |
| `delivery_partner`  | Delivery partner information |

---

## 🔗 Entity Relationships (High Level)
- One user → many orders  
- One order → many order items (`order_details`)  
- Restaurants → menus → food items  
- Each order is assigned to one delivery partner  

---

## 🧠 Business Questions Answered
- The number of orders placed by each customers.
- Restaurant with most number of menu items. 
- Number of votes and average rating for all the restaurants.
- Restaurant with max revenue in a given month (May).
- Restaurant with sales> x
- Customers who have never ordered (using SQL SET operators).
- Show order details of a particular customer in a given date range (Range: 15May- 15 June 2022).
- Find most costly restaurants (Avg price / dish).
- Delivery partner compensation using the formula (#deliveries*100 + 10000*avg_rating).
- All the veg restaurants.
- Minimum and Maximum order value for all the customers.

---
📈 Key Insights

A small percentage of restaurants contribute a disproportionately large share of total platform revenue.

High-value, repeat users have a significant impact on overall earnings.

Certain food items consistently dominate ordering patterns across multiple restaurants.

Delivery partner earnings show a strong correlation with order volume.

🚀 What This Project Demonstrates

Translating business problems into well-structured SQL queries

Writing clean, scalable multi-table JOINs

Accurate revenue computation using line-item–level data

Practical handling of real-world relational database schemas

Analytical thinking that goes beyond basic SQL syntax

📎 How to Use This Repository

Clone or download the repository

Import the SQL files into MySQL

Execute the queries sequentially to explore insights

🤝 Feedback & Collaboration

Feedback, suggestions, and improvements are welcome.
Feel free to connect or raise an issue to discuss this project.
