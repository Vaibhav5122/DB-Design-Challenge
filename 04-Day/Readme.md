# 🚗 Comic-Con Parking System – ER Diagram

This project represents the database design for a multi-zone parking system used during a large Comic-Con event.

---

## 📌 Overview

The system manages vehicle entry, parking allocation, sessions, and payments across different zones and levels in the venue.

Workflow:

- Vehicle enters → ticket is generated
- Parking session starts and a spot is allocated
- Vehicle parks in a suitable spot (based on type/reservation)
- On exit, session ends and payment is calculated

---

## 🧱 Main Entities

- **Vehicles & Vehicle Types** – stores vehicle details and categories
- **Parking Zones & Levels** – structure of the parking facility
- **Parking Spots & Categories** – individual spots with type and reservation rules
- **Parking Tickets** – issued at entry
- **Parking Sessions** – tracks entry, exit, and duration
- **Spot Allocations** – assigns spots to sessions
- **Reservations** – reserved spots for VIP, staff, exhibitors, etc.
- **Pricing Rules** – defines parking charges
- **Payments** – records payment for each session
- **Operators** – staff handling entry/exit

---

## 🔗 Key Relationships

- One vehicle can have multiple parking sessions
- One parking spot can be reused across multiple sessions
- One session is linked to one ticket
- One session can have one or more payments
- Parking spots belong to zones and levels
- Spot reservations define special access categories

---

## 🎯 Key Design Points

- Clear separation of **ticket and parking session**
- Supports **multiple visits by the same vehicle**
- Handles **spot reuse across time**
- Tracks **reserved parking (VIP, staff, EV, etc.)**
- Pricing handled using **configurable rules**
- Can track **currently parked vehicles** using active sessions

---

## 👨‍💻 Author

Vaibhav Waghmode
