# 🛒 FreshMart – Smart Grocery Store (MERN)

## 📌 Overview

FreshMart is a full-stack grocery e-commerce platform built using the MERN stack.
It provides a seamless shopping experience for users and a powerful admin dashboard for managing products, orders, and inventory.

---

## 🚀 Features

### 👤 User Features

* User authentication (Signup/Login)
* Browse products by category
* Search & filter products
* Add to cart & manage cart
* Secure checkout & payment
* Order history & tracking

---

### 🛠️ Admin Features (Single Vendor)

* Dashboard with analytics
* Add / Edit / Delete products
* Manage orders & update status
* Inventory management (stock tracking)
* View transactions & sales

---

## 🧱 Tech Stack

### Frontend (User + Admin)

* React.js (Vite)
* Tailwind CSS
* Zustand (state management)
* React Router

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT Authentication

### Integrations

* Razorpay (Payments)
* Cloudinary (Image Uploads)

---

## 📁 Project Structure

```bash
grocery-store-project/
│
├── frontend/        # User application
├── admin/           # Admin dashboard
├── backend/         # API server
│
├── shared/          # Constants & reusable logic
├── docs/            # Documentation
├── scripts/         # DB scripts
│
├── uploads/         # Local file storage
├── logs/            # Application logs
│
├── docker-compose.yml
├── requirements.md
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/grocery-store-project.git
cd grocery-store-project
```

---

### 2️⃣ Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd ../frontend
npm install
```

#### Admin

```bash
cd ../admin
npm install
```

---

## 🌍 Environment Variables

Create `.env` inside `/backend`:

```env
PORT=5000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret

RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret

CLOUDINARY_NAME=your_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_SECRET=your_secret
```

---

## ▶️ Run Project

### Backend

```bash
cd backend
npm run dev
```

### Frontend

```bash
cd frontend
npm run dev
```

### Admin Panel

```bash
cd admin
npm run dev
```

---

## 🐳 Docker (Optional)

```bash
docker-compose up
```

---

## 📊 Future Improvements

* Real-time inventory (Socket.io)
* AI-based demand prediction
* Delivery tracking system
* Multi-vendor support

---

## 💼 Resume Description

> Built a full-stack grocery e-commerce platform with a separate admin dashboard, secure authentication, payment integration, and scalable architecture using React, Node.js, and MongoDB.

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork and submit pull requests.

---

## 📧 Contact

* Name: Nitish Jha
* Email: nitishjha7710@gmail.com

---

## ⭐ Acknowledgements

Inspired by modern e-commerce platforms and real-world system design practices.
