# SEM-6-smart-canteen
# 🍽️ QR Based Canteen Food Ordering System

The QR Based Canteen Food Ordering System is a full-stack web application designed to simplify food ordering in canteens. It allows users to place orders digitally and receive a QR code, which is scanned by the admin to retrieve order details and serve the correct food efficiently.

---

## 🚀 Features

### 👤 User Side
- View food menu
- Add items to cart
- View total price
- Simulated payment process
- Generate QR code after placing order
- View order details

### 🛠 Admin Side
- Scan QR code
- Retrieve order details
- View ordered items and total amount
- Mark order as completed

---

## 🧱 Tech Stack

### Frontend
- React.js (Vite)
- Tailwind CSS
- React Router
- Context API

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Additional Tools
- QR Code Generation: `qrcode.react`
- QR Scanner: `html5-qrcode`

---

## 📁 Project Structure

qr-canteen-system/
│
├── frontend/
│   ├── index.html
│   ├── src/
│   │   ├── pages/
│   │   │   ├── Login.jsx
│   │   │   ├── Home.jsx
│   │   │   ├── Cart.jsx
│   │   │   ├── Payment.jsx
│   │   │   ├── QRPage.jsx
│   │   │   ├── Admin.jsx
│   │   │
│   │   ├── components/
│   │   │   ├── FoodCard.jsx
│   │   │
│   │   ├── CartContext.jsx
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   ├── index.css
│
├── backend/
│   ├── server.js
│   ├── routes/
│   │   ├── orderRoutes.js
│   ├── models/
│   │   ├── Order.js
│   ├── controllers/
│   │   ├── orderController.js
│   ├── config/
│   │   ├── db.js

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
