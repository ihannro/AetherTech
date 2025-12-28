# 🏢 AetherTech – Modular Inventory, Cart & Order System

AetherTech is a full-stack modular system designed for retail & product-based businesses.  
It includes authentication, product management, cart services, and customer order processing — all powered by microservices architecture and event-driven communication.

---

## 📌 System Overview

This project includes multiple services working together:

### 🧑‍💼 User Service
- Handles user registration, login, and authentication
- Uses **JWT** for secure session handling
- Supports **role-based access control** (Admin / Customer)

### 📦 Product Service
- Admins can **add, update, delete, and manage product inventory**
- Users can browse and view available products

### 🛒 Cart Service
- Customers can add products to cart
- Update item quantities or remove items
- Temporary cart storage before checkout

### 📑 Order Service
- Customers place orders
- Admins can view all orders
- Includes payment simulation / transaction flow

### 📬 RabbitMQ Integration
- Enables asynchronous communication between services
- Example: When order is completed → Product stock automatically updates

### 🖥️ React Dashboard
- Modern responsive frontend using **React + Material UI**
- Admin dashboard + Customer shop interface

### 🐳 Dockerized System
- All services run in isolated containers
- Uses **Docker Compose** for easy startup & deployment

---

## 🛠 Tech Stack

| Category     | Technologies |
|--------------|--------------|
| **Backend**  | Node.js, Express, MongoDB, Mongoose |
| **Auth**     | JWT (JSON Web Token) |
| **Frontend** | React, Material UI |
| **Messaging**| RabbitMQ |
| **DevOps**   | Docker, Docker Compose |

---

## 🌐 Original GitHub Repository

The original source project for AetherTech can be found here ⬇

**https://github.com/akryyydum/Final_Project_SIA.git**
