# 🌾 FarmXchain – AI Driven Agricultural Traceability Network

![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/SpringBoot-Framework-brightgreen)
![React](https://img.shields.io/badge/React-Frontend-blue)
![JWT](https://img.shields.io/badge/JWT-Security-red)
![AI](https://img.shields.io/badge/AI-Gemini-purple)

---

# 📌 Project Overview

**FarmXchain** is a full-stack agricultural supply chain platform designed to improve **transparency, traceability, and trust** in the farm-to-consumer ecosystem.

The platform enables farmers, distributors, retailers, and customers to track agricultural products throughout the supply chain while ensuring secure authentication and reliable product verification.

The system integrates **AI-based product quality analysis**, **secure authentication**, and **role-based dashboards** to provide a modern digital infrastructure for agricultural supply chain management.

---

# 🏆 Internship Project

This project was developed as part of the **Infosys Springboard Internship 6.0 Program**.

The internship focused on building real-world applications using modern technologies including:

* Full-stack web development
* Secure authentication systems
* AI integration
* RESTful API development
* Real-world problem solving in agriculture supply chains

---

# 🚀 Technologies Used

## Backend

* Java
* Spring Boot
* Spring Security
* JWT Authentication
* REST APIs
* Maven

## Frontend

* React.js
* JavaScript
* Tailwind CSS
* Axios

## Database

* MySQL

## AI Integration

* Google Gemini API

## Other Tools

* Cloudinary (Image storage)
* Git & GitHub (Version control)

---

# 🎯 Key Features

✔ Role-based dashboards for different users
✔ Farm and product registration
✔ Supply chain product tracking
✔ AI-powered agricultural quality analysis
✔ Secure JWT authentication
✔ QR-code based product traceability
✔ Transportation tracking between supply chain stages
✔ Responsive modern UI

---

# 👥 User Roles

The system supports multiple stakeholders in the agricultural ecosystem:

**Farmer**

* Register farm details
* Add agricultural products
* Upload product images
* Manage product information

**Distributor**

* Manage product transportation
* Track shipments between locations

**Retailer**

* Manage product distribution and availability

**Customer**

* Scan QR codes
* View product origin and traceability

**Admin**

* Monitor system activities
* Manage platform users

---

# 🧠 AI Quality Check

FarmXchain integrates an **AI-based quality analysis system**.

Product images can be analyzed using AI services to evaluate agricultural product quality and provide insights about crop conditions.

This helps ensure **better quality assurance in the agricultural supply chain**.

---

# 🏗 System Architecture

The backend follows a layered architecture:

```
User
 ↓
React Frontend
 ↓
Spring Boot Backend
 ↓
Service Layer
 ↓
Repository Layer
 ↓
MySQL Database
 ↓
AI Service (Gemini API)
```

This architecture ensures:

* scalability
* maintainable code structure
* clear separation of responsibilities

---

# 📁 Project Structure

```
FarmXchain
│
├── backend
│   ├── controller
│   ├── service
│   ├── repository
│   ├── model
│   ├── security
│   └── config
│
├── src
│   ├── components
│   ├── pages
│   ├── services
│   ├── context
│   └── styles
│
├── public
│   ├── images
│   └── assets
│
├── screenshots
│
├── package.json
├── pom.xml
└── README.md
```

---

# 📸 Application Screenshots

## 🔐 User Authentication

![Login](screenshots/Login.png)

Secure login system with JWT authentication and role-based access control.

---

## 📊 AI Powered Analytics Dashboard

![Analytics Dashboard](screenshots/analytics-dashboard.png)

Interactive dashboard providing analytics and insights related to agricultural product data and system activity.

---

## 🚚 Transportation & Supply Chain Tracking

![Transportation](screenshots/transportation-module.png)

Module used to manage product transportation between origin and destination while visualizing routes.

---

## 🔍 Product Traceability

![Product Traceability](screenshots/product-traceability.png)

Consumers can scan QR codes to track products from **farm to consumer**, ensuring transparency in the supply chain.

---

## 🌾 Farm Registration & Product Management

![Farm Form](screenshots/farmer-form.png)

Farmers can register farms, add products, and include certification and product details.

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the repository

```
git clone https://github.com/jathinvasukula/FarmXchain.git
```

---

## 2️⃣ Backend Setup

```
cd backend
mvn spring-boot:run
```

---

## 3️⃣ Frontend Setup

```
npm install
npm start
```

---

# 📊 Application Modules

* User Authentication
* Product Management
* Farm Registration
* Transportation Tracking
* AI Quality Analysis
* Role-Based Dashboards
* Supply Chain Monitoring

---

# 🔐 Security Implementation

The system implements modern security mechanisms:

* Spring Security
* JWT Token Authentication
* Role Based Access Control

These mechanisms ensure secure communication between the frontend and backend services.

---

# 🌍 Real-World Impact

FarmXchain aims to address several major challenges in agricultural supply chains:

* Lack of transparency in product origin
* Difficulty in tracking supply chain stages
* Quality verification challenges
* Limited trust between farmers and consumers

The platform introduces a **digital traceability network for agricultural products**.

---


## 🎥 Project Highlights

• AI-powered agricultural quality analysis  
• End-to-end farm-to-consumer product traceability  
• Role-based dashboards (Farmer, Distributor, Retailer, Customer, Admin)  
• Secure authentication using JWT  
• Full-stack architecture using React + Spring Boot

---

# 👨‍💻 Author

**Jathin VJ**

Automation Testing | Full Stack Development | Java | Spring Boot | React

---

# 📜 License

This project was developed for **educational and internship purposes** as part of the **Infosys Springboard Internship 6.0 Program**.
