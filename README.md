# 🍽️ Canteen Ordering & Management System – Flask + MongoDB

A full-stack **canteen ordering and management system** built using **Flask** and **MongoDB**, designed for both customers and owners.  
It provides a simple interface for students to order food and for owners to manage menu availability, track orders, and view daily reports.  

---

## 📌 Features

### 👨‍🎓 For Students
- **User Registration & Login** – Secure student account creation.
- **Browse Menu** – View breakfast, break-time snacks, and lunch options.
- **Real-Time Stock Updates** – Shows availability for each item.
- **Order Placement** – Add items to cart and generate a bill.
- **Final Bill** – Includes order number, date, and total price.

### 🛠️ For Owners
- **Owner Login** – Access to menu management and reports.
- **Menu Stock Management** – Add item availability for the day.
- **Daily Auto-Reset** – Menu resets at midnight, breakfast items reset at 10 AM (via APScheduler).
- **View Sales Data** – Track quantity sold for each item and review detailed order history.

---

## 🏗️ Tech Stack
- **Backend:** Flask (Python)
- **Database:** MongoDB (pymongo)
- **Scheduler:** APScheduler for automatic daily menu reset
- **Frontend:** HTML + CSS + Jinja2 Templates
- **Session Management:** Flask sessions
- **Date/Time:** datetime module

---
