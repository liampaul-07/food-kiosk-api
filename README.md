# 🍽️ Food Kiosk Management API

A robust backend service built with **Node.js (Express)** and **MySQL**, designed to streamline quick-service restaurant operations including menu management, inventory control, and order processing.

---

## 🚀 Features

- 👨‍🍳 **Category Management**  
  Create and manage food item categories (e.g., Beverages, Mains, Sides).

- 🍔 **Food Item Management**  
  Add, retrieve, update, and delete individual food items with pricing, stock, and availability status.

- 📦 **Real-Time Inventory Tracking**  
  Update stock levels instantly and automatically reflect item availability.

- 🗑️ **Safe Cascading Delete Logic**  
  Deleting a category first removes all associated food items to maintain data integrity.

- 🛡️ **Input Validation & Sanitization**  
  Prevents invalid or unsafe request data (e.g., empty IDs, malformed strings).

- 🧾 **Advanced Filtering**  
  Retrieve food items filtered by category or inventory status.

- 🌐 **API Testing Support**  
  Fully compatible with Thunder Client and Postman for real-time testing.

---

## 📚 API Endpoints (Summary)

- Categories: `/api/categories` — list, create, update, delete (with cascading food item deletion)  
- Food Items: `/api/fooditems` — list, create, update, delete, filter by category  
- Inventory: `/api/inventory` — update stock, update availability  
- Orders: `/api/orders` — list, create, update status, apply filters  
- Users/Staff: `/api/users` — list, create, update, delete  

---

## 🛠️ Tech Stack

- **Node.js (Express)** — Server framework  
- **MySQL** — Relational database  
- **Postman / Thunder Client** — API testing  


---

## 👨‍💻 Developed By

`[Liam Paul Raboy & ITEK05]`
