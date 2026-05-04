# 🛒 MERN E-Commerce Platform

A full-stack, production-style e-commerce application built using the MERN stack with modern tooling and scalable architecture. This project includes both **customer-facing features** and a fully functional **admin dashboard**.

---

## 🚀 Features

### 🔐 Authentication
- Secure authentication using Clerk
- Role-based access (Admin / Customer)
- Protected routes and session handling

---

### 🛍️ Customer Features
- Browse and filter products
- Product detail pages
- Add to cart and wishlist
- Apply promo codes
- Checkout flow with Razorpay
- Order history
- Address management
- Profile management

---

### 🧑‍💼 Admin Panel
- Dashboard overview
- Product CRUD operations
- Category management
- Promo code management
- Order management
- Homepage banner control
- Application settings

---

## 🧱 Tech Stack

### Frontend
- React (Vite + TypeScript)
- Tailwind CSS + shadcn/ui
- Zustand (state management)
- React Router

### Backend
- Node.js + Express.js
- TypeScript
- MongoDB + Mongoose

### Integrations
- Clerk (Authentication)
- Razorpay (Payments)
- Cloudinary (Image uploads)

---

## 📂 Project Structure

mern-ecommerce-2026  
│  
├── client/        # Frontend (React + Vite)  
├── server/        # Backend (Node + Express)  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

git clone https://github.com/your-username/E-Commerce-Project.git  
cd E-Commerce-Project/mern-ecommerce-2026  

---

### 2️⃣ Backend Setup

cd server  
npm install  
npm run dev  

Backend runs using:  
nodemon + tsx (TypeScript runtime)  

---

### 3️⃣ Frontend Setup

cd client  
npm install  
npm run dev  

Frontend runs using:  
Vite dev server  

---

## 🔑 Environment Variables

### 📌 Server (server/.env)

PORT=5000  
MONGO_URI=your_mongodb_uri  
CLERK_SECRET_KEY=your_clerk_secret_key  
RAZORPAY_KEY_ID=your_key  
RAZORPAY_SECRET=your_secret  
CLOUDINARY_CLOUD_NAME=your_name  
CLOUDINARY_API_KEY=your_key  
CLOUDINARY_API_SECRET=your_secret  

---

### 📌 Client (client/.env)

VITE_API_URL=http://localhost:5000  
VITE_CLERK_PUBLISHABLE_KEY=your_key  

---

## 🔄 Application Flow

1. User authentication via Clerk  
2. Product browsing & filtering  
3. Cart and wishlist management  
4. Promo code application  
5. Checkout using Razorpay  
6. Order creation and tracking  
7. Admin manages products, orders, and settings  

---

## 🧠 Architecture Highlights

- Modular backend structure (routes, models, middleware)  
- Clean separation of frontend and backend  
- Scalable folder organization  
- API-driven communication  
- Type-safe development using TypeScript  

---

## 📊 Key Functional Modules

- Authentication system  
- Product & category management  
- Cart & wishlist system  
- Order lifecycle management  
- Payment integration  
- Admin dashboard  

---

## 🚀 Future Enhancements

- Deployment (Docker / Cloud)  
- Email notifications  
- Performance optimization  
- Unit & integration testing  
- Advanced analytics dashboard  

---

## 👨‍💻 Author

**Sumit Sahoo**

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
