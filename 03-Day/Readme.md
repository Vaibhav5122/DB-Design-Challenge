# 🏥 Clinic Appointment & Diagnostics System – ER Diagram

This project represents the database design for a clinic management system. It handles patient visits, doctor consultations, diagnostic tests, reports, and payments.

---

## 📌 Overview

The system follows a real clinic workflow:

- Patient books an appointment
- Appointment leads to a consultation
- Doctor may prescribe diagnostic tests
- Reports are generated after tests
- Payments are linked to the consultation

---

## 🧱 Main Entities

- **Patients** – stores patient details
- **Doctors** – doctors with specialties
- **Departments & Specialties** – clinic structure
- **Appointments** – booking records
- **Consultations** – actual doctor visits
- **Tests & Test Types** – diagnostic tests
- **Reports** – generated test results
- **Lab Technicians** – staff handling tests
- **Rooms** – used for consultation and diagnostics
- **Payments** – consultation billing

---

## 🔗 Key Relationships

- One patient can have multiple appointments
- One appointment may lead to one consultation
- One consultation can have multiple tests
- Each test generates a report
- Payments are linked to consultations
- Doctors belong to specialties and departments

---

## 🎯 Key Design Points

- Clear separation between **appointment and consultation**
- Tests are linked to **consultations (not appointments)**
- Proper normalization using **test types, departments, and specialties**
- ENUMs used for controlled values like status

---

## 👨‍💻 Author

Vaibhav Waghmode
