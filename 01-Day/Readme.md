# 🛍️ Instagram Thrift Store – ER Diagram

This project contains the database design for an Instagram-based thrift and handmade product store.

---

## 📌 Overview

The system is designed to manage:

- Products (thrift & handmade)
- Customer orders
- Inventory tracking
- Payments and deliveries

It reflects a real-world scenario where a small creator scales from manual order handling to a structured system.

---

## 🧱 Entities

- **Customers** – stores user details
- **Addresses** – multiple addresses per customer
- **Products** – product details (type, size, condition, price)
- **Stock** – tracks available and reserved quantity
- **Orders** – order-level information
- **Order Items** – products inside an order
- **Payments** – payment status and method
- **Deliveries** – shipping and delivery tracking

---

## 🔗 Relationships

- One customer → many orders
- One customer → many addresses
- One order → many products (via order items)
- One product → one stock record
- One order → one payment
- One order → one delivery

---

## 👨‍💻 Author

Vaibhav Waghmode
