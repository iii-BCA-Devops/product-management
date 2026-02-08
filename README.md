# 🧵 Textile Product Management System

A full-stack web application for managing textile products and customer orders.
The project is built using **React (Frontend)** and **Spring Boot (Backend)** with
cloud deployments and CI/CD practices.

---

## 🏗️ Project Architecture

This project follows a **separation of concerns** approach:

- **Frontend** – React application (UI)
- **Backend** – Spring Boot REST API
- Both are maintained as **separate repositories** and deployed independently


---

## 🌐 Live Applications

### Frontend (Vercel)
🔗 https://textile-gt9sxn0cm-productmanagement1.vercel.app

### Backend (Render)
🔗 https://product-management-bxi8.onrender.com/api

---

## 📦 Repositories

- **Frontend Repository**  
  https://github.com/suresh-projects/textile-ui

- **Backend Repository**  
  https://github.com/suresh-projects/product-management

---

## ✨ Features

### Product Management
- Add new textile products
- Update product details
- Delete products
- Search products

### Order Management
- Place orders
- Auto calculate total price
- View order history

---

## 🛠️ Tech Stack

### Frontend
- React
- JavaScript
- HTML / CSS
- Axios / Fetch API
- Vercel Deployment

### Backend
- Java Spring Boot
- REST APIs
- JPA / Hibernate
- MySQL
- Docker
- Render Deployment

---

## ⚙️ Environment Configuration

Frontend uses environment variables for API configuration:

```env
REACT_APP_API_BASE_URL=<backend-api-url>
