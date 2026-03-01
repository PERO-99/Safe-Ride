# 🛡️ SafeRide

SafeRide is a full-stack web platform that enables users to book verified drivers on-demand or schedule them in advance.  
The platform is designed to reduce drunk driving incidents by providing a secure, reliable, and scalable driver booking system.

---

## 🚀 Problem Statement

Drunk driving is a major cause of road accidents, especially in urban areas. Many vehicle owners need a safe alternative when they are unable to drive themselves after late-night events, parties, or emergencies.

SafeRide provides a verified driver booking system with secure payments and ride management to ensure safety and reliability.

---

## 💡 Solution

SafeRide allows users to:

- Register and log in securely  
- Enter pickup and drop locations  
- Get real-time fare estimation  
- Book a verified driver instantly  
- Schedule rides in advance  
- Make secure card payments  
- Rate drivers after ride completion  

---

## 🔐 Core Features

- JWT-based Authentication  
- Password hashing using bcrypt  
- Real-time fare estimation  
- On-demand & scheduled ride booking  
- Driver session management  
- Secure payments via Stripe  
- Saved payment methods  
- Rating & review system  
- User dashboard with ride history  

---

## 🛠️ Tech Stack

### Frontend
- React
- Tailwind CSS
- Vite

### Backend
- Node.js
- Express.js

### Database
- Firebase Firestore

### Authentication
- bcrypt
- JSON Web Tokens (JWT)

### Payments
- Stripe (Test Mode Integrated)

---

## 🏗️ Architecture

Client (React + Tailwind + Vite)  
↓  
Backend API (Node.js + Express)  
↓  
Firebase Firestore  
↓  
Stripe Payment Gateway  

---

## 🔄 User Flow

1. Register  
2. Login  
3. Enter Pickup & Drop Location  
4. View Fare Estimation  
5. Book Driver  
6. Track Ride Session  
7. Complete Payment  
8. Rate Driver  

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/PERO-99/saferide.git
cd saferide
