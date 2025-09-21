# 🏥 Doctor Appointment Booking Website

A full-stack web application for managing doctor appointments with **separate portals for Patients, Doctors, and Admins**.  
Built with **React, TailwindCSS, Node.js, Express.js, MongoDB, Razorpay, and Cloudinary**.  

## 🚀 Live Demo
- **Patient/User App:** [Live Link](https://prescripto-ashy.vercel.app/)  
- **Admin/Doctor App:** [Live Link](https://prescripto-admin-pearl.vercel.app/)  
- **Backend API:** [Live Link](https://prescripto-x3s7.onrender.com/)  

---

## ✨ Features

### 👨‍⚕️ Patient/User Portal
- Browse and filter doctors by specialization  
- View top doctors and detailed doctor profiles (fees, slots, specialization)  
- Book, cancel, or pay for appointments (**Razorpay** or Cash)  
- Manage profile (update details, profile photo via **Cloudinary**)  
- View appointment history  
- About & Contact pages  

### 🛠️ Admin Panel
- Dashboard: total doctors, patients, appointments + latest bookings  
- Manage all appointments  
- Add new doctors  
- View/manage doctors list  

### 👩‍⚕️ Doctor Panel
- Dashboard: personal earnings, total appointments, latest patients  
- Manage appointments (cancel/mark complete)  
- Edit profile  

---

## 🛠 Tech Stack
**Frontend:** React, TailwindCSS, HTML, CSS, JavaScript  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Payments:** Razorpay Integration  
**Media Storage:** Cloudinary  
**Deployment:** Vercel (Frontend), Render (Backend)  

---


---

## 🔑 Test Credentials

### Admin Login
- **Email:** admin@example.com  
- **Password:** admin123  

### Doctor Login
- **Email:** doctor@example.com  
- **Password:** doctor123  


---

## ⚡ Getting Started (Run Locally)

### 1. Clone Repository
### 2. Backend Setup
```bash
git clone https://github.com/your-username/doctor-appointment-booking.git
cd doctor-appointment-booking


cd backend
npm install

Create a .env file inside backend/ with the following:

MONGO_URI=your_mongo_uri
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
JWT_SECRET=your_jwt_secret
PORT=5000

Run backend
npm start

