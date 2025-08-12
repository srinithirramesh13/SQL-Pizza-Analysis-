# SQL-Pizza-Analysis-
# 🍕 Pizza Sales SQL Analysis

## 📌 Overview
The **Pizza Sales SQL Analysis** project uses SQL queries to explore and analyze sales performance for a pizza business.  
The dataset includes details about pizzas, pizza types, orders, and order details, enabling comprehensive business insights such as **top-selling pizzas, revenue trends, and ordering patterns**.

---

## 🎯 Objectives
- Analyze total orders and revenue.
- Identify **top-selling pizzas** by quantity and revenue.
- Explore **category-wise sales distribution**.
- Determine **sales trends** by time and date.
- Calculate **average pizzas sold per day**.
- Track **cumulative revenue growth** over time.

---

## 📂 Dataset Structure
The database `pizza_hut` contains the following tables:

1. **orders**
   - `order_id` – Unique order identifier.
   - `date` – Order date.
   - `time` – Order time.

2. **order_details**
   - `order_details_id` – Unique detail ID.
   - `order_id` – Links to `orders`.
   - `pizza_id` – Links to `pizzas`.
   - `quantity` – Number of pizzas ordered.

3. **pizzas**
   - `pizza_id` – Unique pizza identifier.
   - `pizza_type_id` – Links to `pizza_types`.
   - `size` – Size of the pizza.
   - `price` – Price per pizza.

4. **pizza_types**
   - `pizza_type_id` – Unique pizza type identifier.
   - `name` – Pizza name.
   - `category` – Pizza category.
   - `ingredients` – Ingredients used.

---

## 📊 Key Analyses Performed
- **Basic Analysis**
  - Total orders placed.
  - Total revenue generated.
  - Highest-priced pizza.
  - Top 5 most ordered pizzas.

- **Intermediate Analysis**
  - Quantity sold by pizza category.
  - Orders distribution by hour.
  - Category-wise pizza distribution.
  - Average pizzas sold per day.
  - Top 3 pizzas by revenue.

- **Advanced Analysis**
  - Revenue contribution percentage by pizza type.
  - Cumulative revenue over time.
  - Top 3 pizzas by revenue per category.

---

## 🛠 Tools & Technologies
- **SQL Database:** MySQL
- **Analysis Tool:** MySQL Workbench / SQL CLI

---

## 🚀 How to Run
1. Create a new MySQL database named `pizza_hut`.
2. Import the dataset and table structure from the provided `.sql` file.
3. Execute the SQL queries to generate insights.
4. Modify queries to explore specific business questions.

---

## 💬 Closing Note
Thank you for taking the time to check out my project!  
I hope this analysis provides useful insights into pizza sales performance.  
Your feedback is always welcome and will help me improve and grow.

---

## 📩 Contact
- **Email:** [srinithirramesh13@gmail.com](mailto:srinithirramesh13@gmail.com)  
- **GitHub:** [github.com/srinithirramesh13](https://github.com/srinithirramesh13)

---

