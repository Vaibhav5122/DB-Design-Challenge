# 🏋️ Fitness Coaching Platform – ER Diagram

This project shows the database design for an online fitness coaching platform.

---

## 📌 Overview

The platform allows trainers to manage clients, sell coaching plans, schedule sessions, and track client progress.

---

## 🧱 Main Components

- **Users** – stores both trainers and clients
- **Plans** – coaching programs created by trainers
- **Subscriptions** – tracks which client bought which plan
- **Sessions** – scheduled meetings between trainer and client
- **Check-ins** – weekly updates submitted by clients
- **Progress Logs** – stores fitness data like weight, body fat, measurements
- **Payments** – tracks subscription payments

---

## 🔗 Relationships

- One trainer can create multiple plans
- One client can subscribe to multiple plans
- One plan can have many clients
- One client can attend multiple sessions
- One client can submit multiple check-ins
- One client can have multiple progress records
- One subscription can have multiple payments

---

## 🎯 Key Points

- Plans and subscriptions are handled separately
- Sessions and check-ins are different
- Progress tracking is stored separately from user data
- The design is simple, scalable, and practical

---

## 👨‍💻 Author

Vaibhav Waghmode
