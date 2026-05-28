# World-Cart 🛒

World-Cart is a full-stack menswear e-commerce web application developed using Node.js, Express.js, MongoDB, HTML, CSS, and JavaScript. The platform allows users to browse products, create accounts, manage carts, and place orders with a responsive and modern shopping experience.

---

## 🚀 Features

### 👤 User Features

* User Signup & Login
* JWT Authentication
* View Products
* Product Details Page
* Add to Cart
* Update Cart Quantity
* Checkout System
* Order Placement
* User Profile

### 🛠️ Admin Features

* Admin Authentication
* Add Products
* Manage Products
* View Orders

---

## 🧑‍💻 Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas
* Mongoose

### Authentication

* JWT (JSON Web Token)
* bcrypt

---

## 📁 Project Structure

```text
World-cart/
│
├── backend/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── db.js
│   ├── server.js
│   └── .env
│
├── frontend/
│   ├── admin/
│   ├── css/
│   ├── js/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── products.html
│   ├── product.html
│   ├── cart.html
│   ├── checkout.html
│   ├── orders.html
│   └── server.js
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Shivam291-nayak/world-cart-Ecommerce-website.git
```

---

### 2️⃣ Open Project Folder

```bash
cd world-cart-Ecommerce-website
```

---

## 🔧 Backend Setup

### Install Dependencies

```bash
cd backend
npm install
```

### Create `.env` File

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
ADMIN_EMAIL=admin@menswear.com
```

### Run Backend

```bash
npm start
```

Backend runs on:

```text
http://localhost:5000
```

---

## 🎨 Frontend Setup

### Install Dependencies

```bash
cd frontend
npm install
```

### Run Frontend

```bash
npm start
```

Frontend runs on:

```text
http://localhost:3000
```

---

## 🔗 API Endpoints

### Authentication

```text
POST /api/auth/signup
POST /api/auth/login
```

### Products

```text
GET /api/products
GET /api/products/:id
POST /api/products
```

### Cart

```text
POST /api/cart/add
GET /api/cart
DELETE /api/cart/remove/:id
PUT /api/cart/update
```

### Orders

```text
POST /api/orders/create
GET /api/orders/my
```

---

## 📸 Screenshots

* Home Page
* Login Page
* Product Listing
* Product Details
* Cart Page
* Admin Dashboard

---

## 🌐 GitHub Repository

[World-Cart Repository](https://github.com/Shivam291-nayak/world-cart-Ecommerce-website?utm_source=chatgpt.com)

---

## 👨‍💻 Developer

**Shivam Nayak**
B.Tech CSE Student
Java Full Stack & Backend Developer

---

## 📜 License

This project is developed for educational and learning purposes.
