


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Forever%20Fashion&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=55&desc=Modern%20Full%20Stack%20MERN%20E-Commerce%20Platform&descAlignY=78&descSize=18" width="100%"/>

<br/>

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Now-00d4ff?style=for-the-badge\&labelColor=0d1117)](https://forever-frontend-jgifxgwlo-anurag-singhs-projects-f7753076.vercel.app)

[![GitHub](https://img.shields.io/badge/GitHub-Source_Code-ffffff?style=for-the-badge\&logo=github\&logoColor=white\&labelColor=0d1117)](https://github.com/ab6207/forever-full-stack)

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![Stars](https://img.shields.io/github/stars/ab6207/forever-full-stack?style=flat-square\&color=00d4ff\&labelColor=0d1117)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square\&labelColor=0d1117)

</div>

---

## 📖 Overview

**Forever Fashion** is a production-ready full-stack e-commerce platform built using the **MERN Stack**. It provides a complete online shopping experience where users can browse products, search collections, manage carts, place orders, and complete secure payments.

The platform also includes a dedicated **Admin Dashboard** for product management, order handling, and inventory control.

> A real-world MERN application demonstrating authentication, authorization, cloud image storage, payment integration, and scalable REST APIs.

---

## ✨ Features

### 👤 Customer Panel

* 🔐 User Registration & Login
* 🛒 Add to Cart & Remove from Cart
* 🔍 Search and Filter Products
* ❤️ Wishlist Management
* 📦 Place Orders
* 💳 Secure Stripe Payments
* 📜 Order History
* 📱 Fully Responsive UI

### 👨‍💼 Admin Panel

* ➕ Add New Products
* ✏️ Update Existing Products
* ❌ Delete Products
* 📦 Manage Customer Orders
* 📊 Dashboard Overview
* 🖼️ Upload Product Images

### 🔒 Authentication & Security

* 🔑 JWT Authentication
* 🔐 Protected Routes
* 🛡️ Role-Based Authorization
* ✅ Secure REST APIs

### ☁️ Cloud Services

* Cloudinary Image Uploads
* Optimized Media Delivery
* Secure Asset Management

---

## 🛠️ Tech Stack

| Layer          | Technology                    |
| -------------- | ----------------------------- |
| Frontend       | React.js, Tailwind CSS, Axios |
| Backend        | Node.js, Express.js           |
| Database       | MongoDB, Mongoose             |
| Authentication | JWT                           |
| Payments       | Stripe                        |
| Image Storage  | Cloudinary                    |
| Deployment     | Vercel                        |

<div align="center">

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square\&logo=react\&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square\&logo=node.js\&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square\&logo=express\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square\&logo=mongodb\&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square\&logo=tailwindcss\&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square\&logo=jsonwebtokens\&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square\&logo=stripe\&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square\&logo=cloudinary\&logoColor=white)

</div>

---

## 📁 Project Structure

```text
forever-full-stack/
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   └── context/
│
├── admin/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   └── assets/
│
├── screenshots/
│   ├── Home.png
│   ├── Product.png
│   ├── Cart.png
│   └── admin.png
│
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

```bash
Node.js >= 18
MongoDB Atlas
Cloudinary Account
Stripe Account
```

### Clone Repository

```bash
git clone https://github.com/ab6207/forever-full-stack.git

cd forever-full-stack
```

### Backend Setup

```bash
cd backend

npm install

npm run server
```

Create a `.env` file:

```env
PORT=4000

MONGODB_URI=your_mongodb_uri

JWT_SECRET=your_jwt_secret

CLOUDINARY_NAME=your_cloudinary_name

CLOUDINARY_API_KEY=your_cloudinary_api_key

CLOUDINARY_SECRET_KEY=your_cloudinary_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
```

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

### Admin Setup

```bash
cd admin

npm install

npm run dev
```

---

## 🔗 API Endpoints

### Authentication

| Method | Endpoint           |
| ------ | ------------------ |
| POST   | /api/user/register |
| POST   | /api/user/login    |

### Products

| Method | Endpoint            |
| ------ | ------------------- |
| GET    | /api/product/list   |
| POST   | /api/product/add    |
| DELETE | /api/product/remove |

### Orders

| Method | Endpoint              |
| ------ | --------------------- |
| POST   | /api/order/place      |
| GET    | /api/order/userorders |
| GET    | /api/order/list       |

---

## 📸 Application Preview

### 🏠 Home Page

<p align="center">
  <img src="./screenshots/Home.png" width="100%">
</p>

---

### 📦 Product Page

<p align="center">
  <img src="./screenshots/Product.png" width="100%">
</p>

---

### 🛒 Cart Page

<p align="center">
  <img src="./screenshots/Cart.png" width="100%">
</p>

---

### 👨‍💼 Admin Dashboard

<p align="center">
  <img src="./screenshots/admin.png" width="100%">
</p>

---

## 🌐 Live Demo

🔗 https://forever-frontend-jgifxgwlo-anurag-singhs-projects-f7753076.vercel.app/

---

## 👨‍💻 Author

**Anurag Singh**

🎓 B.Tech CSE (2027) — IIIT Bhopal

💻 MERN Stack Developer

🧩 DSA Enthusiast

🚀 Open to SDE & Full Stack Opportunities

GitHub: https://github.com/ab6207

---

<div align="center">

⭐ **Star this repository if you found it useful!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=80&section=footer" width="100%"/>

</div>


<div align="center">

Made with ❤️ using MERN Stack

</div>
