# 🛒 MockMall

**MockMall** is a sample **E-commerce web application** built for **Devian Agency** to showcase scalable, modern, and developer-friendly e-commerce solutions.  
This project acts as a **demonstration model** for clients and internal development, highlighting how Devian structures, designs, and deploys web applications.

---

## ✨ Why MockMall?

E-commerce is one of the most common yet complex web application categories. MockMall was built to:

- ✅ Provide a **sample e-commerce store** for Devian’s portfolio.  
- ✅ Demonstrate **best practices** in modern full-stack development.  
- ✅ Showcase **Devian’s capabilities** in UI/UX, backend engineering, and scalability.  
- ✅ Serve as a **starter template** for future e-commerce projects.  
- ✅ Act as a **teaching/demo tool** for new developers at Devian.

---

## 🔎 What is MockMall?

MockMall is not a production-ready store but a **demo project**. It simulates an online shopping experience with:

- 🛍️ Product listing, search, and filtering  
- 🧾 Cart and checkout flow  
- 👤 Basic user authentication (login, register)  
- 📦 Order placement simulation  
- 🎨 Responsive and modern UI (Devian Design System)  
- ⚡ Scalable backend structure with hybrid caching  

---

## 🌍 Where is it used?

- **Devian Agency Portfolio** → Showcasing client-ready e-commerce solutions.  
- **Demo to Clients** → As a starting point for customized e-commerce apps.  
- **Internal Devian Development** → Acts as a boilerplate for future e-commerce builds.  
- **Learning Resource** → Teaching Devian’s junior devs about modern web stacks.  

---

## ⚙️ How does it work?

### 🏗️ Tech Stack

**Frontend**  
- Next.js (TypeScript)  
- Tailwind CSS (Custom Devian UI Kit)  
- Zustand / Redux for state management  

**Backend**  
- Express.js / Node.js  
- MongoDB + Redis (hybrid approach for caching + scalability)  
- RESTful APIs with proper controllers  

**Other Integrations**  
- Cloudinary (media & file storage)  
- Razorpay (dummy checkout/payment simulation)  
- Session & Token-based authentication  

---

## 🔧 Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/devian-agency/mockmall.git
cd mockmall
```
### 2. Install Dependencies
```bash
yarn
```
### 3. Environment variable
```bash
# Database
MONGO_URI=your_mongo_url
REDIS_URL=your_redis_url

# Cloudinary
CLOUDINARY_NAME=xxxx
CLOUDINARY_API_KEY=xxxx
CLOUDINARY_API_SECRET=xxxx

# Razorpay (Test Mode)
RAZORPAY_KEY=xxxx
RAZORPAY_SECRET=xxxx

# Authentication
SESSION_SECRET=xxxx
JWT_SECRET=xxxx
```
### 4. Run Development Server
```bash
yarn dev
```
### 5. Build for Production
```bash
yarn build
yarn start
```

## 🚀 Features

- 🔥 Modern & responsive UI with Tailwind + custom components
- 🔍 Smart search & product filtering
- 🛒 Cart management with local & server sync
- 📦 Simulated checkout & order system
- 🔐 Authentication (sessions + JWT)
- ⚡ Redis caching for performance
- ☁️ Cloudinary integration for product images
- 💳 Razorpay integration (test mode)

## 🧩 Project Needs

To extend MockMall into a full-scale production-ready store, it would require:

- Robust Authentication → OAuth2, TOTP, and multi-device sessions
- Admin Dashboard → For product, order, and user management
- Inventory Management System → Real-time stock sync
- Payment Gateway Production Mode → Full Razorpay/Stripe integration
- Scalable Hosting → Vercel (frontend), Render/Heroku/AWS (backend)
- CI/CD Pipeline → Automated deployment & testing

## 🛠️ Development Roadmap

- Product Reviews & Ratings
- Wishlist & Saved Items
- Multi-vendor Support
- Real-time Notifications (Socket.io)
- AI-powered Product Recommendations

## 📌 Then (Future of MockMall)

MockMall will evolve into:

- A ready-to-deploy boilerplate for Devian clients.
- A training project for Devian’s in-house team.
- A case study to showcase Devian’s design & development excellence.

## 👨‍💻 Contributing
This is an internal Devian project. Contributions are limited to the Devian development team.
For suggestions or client-specific customizations, contact Devian Agency.

## 📬 Contact

Devian Agency
- 🌐 Website: https://devian.in
- 📧 Email: devian.agency@gmail.com
- 📍 Founder & CEO: Gajender
