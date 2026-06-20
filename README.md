<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a1a,100:2d2d2d&height=220&section=header&text=Forever%20Fashion&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=48&desc=Modern%20Full%20Stack%20MERN%20E-Commerce%20Platform&descAlignY=70&descSize=20&descColor=cccccc" width="100%"/>


<br/>

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Now-7c3aed?style=for-the-badge&labelColor=0d1117)](https://forever-frontend-jgifxgwlo-anurag-singhs-projects-f7753076.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Source_Code-ffffff?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117)](https://github.com/ab6207/forever-full-stack)
[![License](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge&labelColor=0d1117)](LICENSE)

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Stars](https://img.shields.io/github/stars/ab6207/forever-full-stack?style=flat-square&color=a78bfa&labelColor=0d1117)
![Last Commit](https://img.shields.io/github/last-commit/ab6207/forever-full-stack?style=flat-square&color=60a5fa&labelColor=0d1117)

</div>

---

## 📖 Overview

**Forever Fashion** is a production-ready, full-stack e-commerce platform built with the **MERN Stack**. It delivers a complete online shopping experience — from browsing collections and managing carts to placing orders and processing secure payments.

A dedicated **Admin Dashboard** handles product management, order tracking, and inventory control — making it a fully operational end-to-end solution.

> Built to demonstrate real-world engineering: JWT auth, role-based access, Cloudinary media storage, Stripe payments, and scalable REST APIs — all deployed on Vercel.

---

## ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 👤 Customer Panel
- 🔐 User Registration & Secure Login
- 🛒 Add to Cart / Remove from Cart
- 🔍 Search & Filter Products by Category
- ❤️ Wishlist Management
- 📦 Place Orders with Address Management
- 💳 Secure Stripe Payments
- 📜 Order History & Tracking
- 📱 Fully Responsive UI

</td>
<td width="50%" valign="top">

### 👨‍💼 Admin Panel
- ➕ Add New Products with Images
- ✏️ Update / Edit Existing Products
- ❌ Delete Products
- 📦 Manage & Update Order Status
- 📊 Dashboard Overview
- 🖼️ Cloudinary Image Upload & Preview

</td>
</tr>
<tr>
<td valign="top">

### 🔒 Security
- 🔑 JWT-based Authentication
- 🛡️ Role-Based Route Authorization
- 🔐 Protected API Endpoints
- ✅ Input Validation & Error Handling

</td>
<td valign="top">

### ☁️ Cloud & Infra
- 📸 Cloudinary Image Uploads
- ⚡ Optimized Media Delivery (CDN)
- 🌐 Deployed on Vercel (Frontend + Admin)
- 🗄️ MongoDB Atlas (Cloud Database)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React.js, Tailwind CSS, Axios, React Router |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB, Mongoose |
| **Authentication** | JSON Web Tokens (JWT) |
| **Payments** | Stripe |
| **Image Storage** | Cloudinary |
| **Deployment** | Vercel |

<div align="center">

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</div>

---

## 📁 Project Structure

```
forever-full-stack/
│
├── 📂 backend/
│   ├── controllers/        # Route logic & business layer
│   ├── middleware/         # Auth middleware (JWT verify, admin check)
│   ├── models/             # Mongoose schemas (User, Product, Order)
│   ├── routes/             # API route definitions
│   └── server.js           # Express app entry point
│
├── 📂 frontend/
│   └── src/
│       ├── assets/         # Static images & icons
│       ├── components/     # Reusable UI components (Navbar, Footer, etc.)
│       ├── pages/          # Page views (Home, Product, Cart, Orders...)
│       └── context/        # React Context (Cart state, Auth state)
│
├── 📂 admin/
│   └── src/
│       ├── pages/          # Admin pages (Add Product, Orders, List)
│       ├── components/     # Admin UI components (Sidebar, Navbar)
│       └── assets/         # Admin static assets
│
├── 📂 screenshots/         # App preview images
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following set up before running the project:

```
Node.js >= 18
MongoDB Atlas account
Cloudinary account
Stripe account
```

### 1. Clone the Repository

```bash
git clone https://github.com/ab6207/forever-full-stack.git
cd forever-full-stack
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` directory:

```env
PORT=4000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

Start the backend server:

```bash
npm run server
```

### 3. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### 4. Admin Panel Setup

```bash
cd admin
npm install
npm run dev
```

> The frontend runs on `http://localhost:5173` and the backend on `http://localhost:4000` by default.

---

## 🔗 API Reference

### 🔐 Authentication

| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/api/user/register` | Register a new user |
| `POST` | `/api/user/login` | Login and receive JWT token |
| `POST` | `/api/user/admin` | Admin login |

### 🛍️ Products

| Method | Endpoint | Access | Description |
|--------|----------|--------|-------------|
| `GET` | `/api/product/list` | Public | Get all products |
| `GET` | `/api/product/single` | Public | Get single product by ID |
| `POST` | `/api/product/add` | Admin | Add a new product |
| `POST` | `/api/product/remove` | Admin | Remove a product |

### 📦 Orders

| Method | Endpoint | Access | Description |
|--------|----------|--------|-------------|
| `POST` | `/api/order/place` | User | Place a COD order |
| `POST` | `/api/order/stripe` | User | Place a Stripe payment order |
| `GET` | `/api/order/userorders` | User | Get orders for logged-in user |
| `GET` | `/api/order/list` | Admin | Get all orders |
| `POST` | `/api/order/status` | Admin | Update order delivery status |

### 🛒 Cart

| Method | Endpoint | Access | Description |
|--------|----------|--------|-------------|
| `POST` | `/api/cart/add` | User | Add item to cart |
| `POST` | `/api/cart/update` | User | Update cart item quantity |
| `POST` | `/api/cart/get` | User | Get user cart data |

---

## 📸 Application Preview

### 🏠 Home Page
<p align="center">
  <img src="./screenshots/Home.png" width="100%" alt="Home Page"/>
</p>

### 📦 Product Page
<p align="center">
  <img src="./screenshots/Product.png" width="100%" alt="Product Page"/>
</p>

### 🛒 Cart Page
<p align="center">
  <img src="./screenshots/Cart.png" width="100%" alt="Cart Page"/>
</p>

### 👨‍💼 Admin Dashboard
<p align="center">
  <img src="./screenshots/admin.png" width="100%" alt="Admin Dashboard"/>
</p>

---

## 🌐 Live Demo

> 🔗 **[https://forever-frontend-jgifxgwlo-anurag-singhs-projects-f7753076.vercel.app](https://forever-frontend-jgifxgwlo-anurag-singhs-projects-f7753076.vercel.app)**

---

## 👨‍💻 Author

<div align="center">

**Anurag Singh**

🎓 B.Tech CSE (2027) — IIIT Bhopal &nbsp;|&nbsp; 💻 MERN Stack Developer &nbsp;|&nbsp; 🧩 DSA Enthusiast

[![GitHub](https://img.shields.io/badge/GitHub-ab6207-181717?style=for-the-badge&logo=github)](https://github.com/ab6207)

🚀 *Open to SDE & Full Stack Opportunities*

</div>

---

⭐ **If this project helped you, please consider giving it a star!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2d2d2d,100:1a1a1a&height=100&section=footer&text=Built%20with%20%E2%9D%A4%EF%B8%8F%20using%20MERN%20Stack&fontSize=18&fontColor=cccccc&animation=fadeIn&fontAlignY=65" width="100%"/>

</div>
