# 🛒 MockMall – E-Commerce Sample Project

MockMall is a **sample e-commerce platform** developed by **Devian Agency** to demonstrate **modern web application architecture**, **best practices**, and **scalable design patterns**.  
It acts as a **reference implementation** for internal projects and as a **client showcase** to highlight Devian’s technical and design expertise.  

---

## 📖 Table of Contents

- [Overview](#-overview)  
- [Why MockMall](#-why-mockmall)  
- [Scope](#-scope)  
- [System Architecture](#-system-architecture)  
- [Technology Stack](#-technology-stack)  
- [Features](#-features)  
- [Setup & Installation](#-setup--installation)  
- [Environment Variables](#-environment-variables)  
- [Development Workflow](#-development-workflow)  
- [Roadmap](#-roadmap)  
- [Future Direction](#-future-direction)  
- [License](#-license)  
- [Contact](#-contact)  

---

## 📝 Overview

**MockMall** is designed to:  

- Showcase Devian’s capability in building **enterprise-grade e-commerce applications**.  
- Provide a **reference architecture** for future e-commerce projects.  
- Demonstrate a **scalable hybrid data model** using **MongoDB + Redis**.  
- Serve as a **developer onboarding project** to align with Devian’s engineering standards.  

---

## 🎯 Why MockMall

- **Client Demonstration** → A ready-to-show sample project for prospects.  
- **Standardization** → Establishes a baseline structure for future Devian projects.  
- **Internal Training** → Helps new developers understand Devian’s code practices.  
- **Innovation Sandbox** → A testing ground for integrating new tools, APIs, and workflows.  

---

## 📦 Scope

MockMall simulates a complete shopping flow:  

- Product catalog with filters & search  
- Cart management (client + server sync)  
- Checkout with payment simulation  
- Authentication (sessions + JWT)  
- Order management (demo mode)  
- Responsive, scalable, and optimized UI  

---

## 🛠️ Technology Stack

### Frontend
- **Next.js (TypeScript)** → SSR + SSG for performance  
- **Tailwind CSS + Devian UI Kit** → Scalable, responsive design  
- **State Management** → Zustand / Redux  

### Backend
- **Express.js (Node.js)** → RESTful API layer  
- **MongoDB** → Persistent product, order, user data  
- **Redis** → Real-time caching for sessions and product queries  

### Integrations
- **Cloudinary** → Media & asset storage  
- **Razorpay (Test Mode)** → Payment simulation  
- **Authentication** → Sessions + JWT  

---

## 🚀 Features

- Modern & responsive UI with reusable components  
- Product search, filtering, and sorting  
- Cart persistence (local + server sync)  
- Simulated checkout process  
- User authentication & sessions  
- Cloud-based media management  
- Caching layer for scalability  

---

## ⚙️ Setup & Installation

### 1. Clone Repository
```bash
git clone https://github.com/devian-agency/mockmall.git
cd mockmall
```
### 2. Install Dependencies
```bash
yarn
```

### 3. Configure .env
```bash
# Database
MONGO_URI=your_mongo_url
REDIS_URL=your_redis_url

# Cloudinary
CLOUDINARY_NAME=xxxx
CLOUDINARY_API_KEY=xxxx
CLOUDINARY_API_SECRET=xxxx

# Razorpay
RAZORPAY_KEY=xxxx
RAZORPAY_SECRET=xxxx

# Authentication
SESSION_SECRET=xxxx
JWT_SECRET=xxxx

```

### 4. Run Application
```bash
npm run dev       # development
npm run build     # build for production
npm start         # run production build
```

---

## 🔄 Development Workflow

- **Branching** → `main` (stable), `dev` (active development), feature branches per task  
- **Commits** → Conventional commits (`feat:`, `fix:`, `docs:`, etc.)  
- **CI/CD** → Automated testing & deployment (planned)  
- **Code Quality** → Prettier + ESLint enforced  

---

## 📌 Roadmap

- [ ] Product reviews & ratings  
- [ ] Wishlist & saved items  
- [ ] Admin dashboard (product & order management)  
- [ ] Real payment gateway integration (Stripe/Razorpay live)  
- [ ] Real-time notifications with WebSockets  

---

## 🔮 Future Direction

MockMall is envisioned to evolve into:  

- A **ready-to-deploy e-commerce boilerplate** for Devian clients  
- A **training ground** for onboarding engineers  
- A **showcase platform** demonstrating Devian’s design + dev synergy  
- An **accelerator template** to reduce delivery time for e-commerce solutions  

---

## 📜 License

This project is proprietary and maintained by **Devian Agency**.  
Unauthorized distribution or usage outside Devian is prohibited.  

---

## 📬 Contact

**Devian Agency**  
🌐 Website: [Devian](https://devian.agency)  
📧 Email: devian.agency@gmail.com  
👨‍💻 Founder & CEO: Gajender  

---



