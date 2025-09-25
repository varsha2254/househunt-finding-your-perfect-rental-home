# 🏡 HouseHunt: Finding Your Perfect Rental Home  

A full-stack web application built with the **MERN Stack (MongoDB, Express.js, React, Node.js)** that simplifies the home rental process by connecting **renters, property owners, and admins** on one platform.  

HouseHunt eliminates the need for third-party brokers and provides secure, role-based access for property listing, booking, and management.  

---

## 🚀 Features  

### 🔐 User Roles & Authentication  
- Secure JWT-based login & registration  
- Role-based access: **Renter, Owner, Admin**  
- Protected routes with middleware  

### 🏘️ Property Listings  
- Owners can **add, edit, delete, and manage** properties  
- Support for images, categories, price, location & availability  
- Responsive listing cards with search & filter  

### 🔍 Advanced Search & Filtering  
- Search by **location, type, category, price, and facilities**  
- Real-time filtered display  

### 📆 Booking & Inquiry System  
- Renters can **book or inquire** about a property  
- Owners manage booking requests  
- Booking records linked to users  

### 🛠️ Admin Dashboard  
- Manage users, properties, and bookings  
- Approve or remove listings  
- Monitor platform activity  

### 💡 Additional Highlights  
- **Responsive UI** with React + Tailwind CSS  
- RESTful APIs with Express.js  
- MongoDB with Mongoose for structured data  
- Modular, scalable architecture  

---

## 🏗️ Architecture  

- **Frontend:** React.js + Tailwind CSS  
- **Backend:** Node.js + Express.js  
- **Database:** MongoDB Atlas (via Mongoose)  
- **Authentication:** JWT (JSON Web Tokens)  

Data Flow:  
1. User logs in → JWT issued  
2. Renter searches listings → API filters DB results  
3. Owner adds property → Stored in DB  
4. Renter books → Booking stored & linked  
5. Admin reviews listings/bookings  

---

## ⚡ Tech Stack  

- **Frontend:** React, Tailwind CSS, Axios, React Router  
- **Backend:** Node.js, Express.js, JWT, bcrypt  
- **Database:** MongoDB, Mongoose  
- **Other Tools:** Postman (API testing), Git, VS Code  

---

## 📦 Setup Instructions  

### Prerequisites  
- Node.js (v16+)  
- MongoDB Atlas or Local MongoDB  
- Git  

### Backend Setup  
```bash
cd server
npm install
# Create a .env file with:
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000

npm run dev
```
### Frontend Setup
```bash
cd client
npm install
npm run dev
