# E-commerce Web Application

React • Spring Boot • MySQL

A modern e-commerce application that allows users to browse products, manage a shopping cart, and place orders. Includes secure authentication and a dedicated admin panel to manage products and orders.

🌐 Live Demo

✨ Key Features
For Customers
🔐 User Registration & Login – JWT-secured authentication
🛍️ Product Browsing – View, filter, and search products
🛒 Shopping Cart – Add, update, and remove products with automatic total calculation
📦 Order Creation – Place orders from the cart
👤 Profile Management – Update personal details

For Admins
🛠️ Admin Dashboard – Manage products and orders
➕ Product CRUD – Add, edit, and delete products
📋 Order Management – View and manage customer orders
🔐 Role-Based Access – Admin-only functionalities protected by JWT

🧩 Modules Overview
1. User Module
•Register and log in securely
•Password hashing using bcrypt
•Role-based access (Customer / Admin)
•Update profile information

2. Product Module
•Admin can add/edit/delete products
•Product details include: name, price, description, image
•Users can browse and search products easily

3. Cart Module
•Add items to cart
•Update quantity
•Remove items
•Auto total calculation
•Cart persists during session

4. Order Module
•Convert cart items into an order
•Store order details
•Users can view order history
•Admins can track all orders

🛠️ Tech Stack
•Frontend: React 19, CSS, React Router v6, React Hook Form
•Backend: Spring Boot 3.5.6, REST API, MySQL Database
•Security: JWT Authentication, bcrypt password hashing

🏗️ Project Architecture
src/
├── components/
│   └── layout/
│       └── RootLayout.jsx
│
├── pages/
│   ├── Register.jsx
│   ├── Login.jsx
│   ├── Home.jsx
│   ├── AdminPage.jsx
│   ├── ProductCard.jsx
│   ├── ViewProduct.jsx
│   ├── EditProductPage.jsx
│   ├── DeleteProductPage.jsx
│   ├── CartPage.jsx
│   ├── CheckoutPage.jsx
│   └── UserProfileUpdate.jsx
│
├── App.css
└── App.jsx

🚀 Deployment
Frontend: Netlify
Backend: Railway
Database: MySQL (Railway)
