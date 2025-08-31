# WEARBEST FASHIONS  

An e-commerce demo website for **Wearbest Fashions**. The project showcases a full multipage site with **customer and admin panels**, shopping cart, checkout, and inventory management. It was built with **HTML5, CSS3, and JavaScript**, and organized for production-ready deployment.  

---

## 🌐 Project Purpose  

The purpose of this website is to simulate a working online store for **Wearbest Fashions** (Kapsabet). It demonstrates:  
- A **customer experience** (browsing products, managing cart, checkout, placing orders).  
- An **admin experience** (inventory management, customer orders, sales, receipt generation).  
- **Responsive and modern design**, with semantic HTML and reusable components.  

This project is part of a final assignment to build, organize, and deploy a **multi-page website** that’s interactive, mobile-friendly, and well-structured.  

---

## 📂 Project Structure  

```bash
wearbest-fashions/
│
├── index.html          # Homepage with cart, checkout, customer account
├── account.html        # Manage customer orders & statuses

├── login.html          # Customer login/signup + password reset
├── products.html       # Product listing (product1.jpg – product8.jpg)
├── /admin/             # Admin panel (separate login), Generate POS receipts, View sales reports
│
├── /css/
│   └── style.css       # Main styles (navy blue theme, responsive design)
│
├── /js/
│   ├── app.js         # Customer side logic (cart, checkout, forms) Admin panel logic
│
├── /images/            # Product images
│   ├── product1.jpg
│   ├── product2.jpg
│   └── ... product8.jpg
│
└── README.md           # Project documentation
```

---

## ✨ Features  

### 👤 Customer Panel  
- **Responsive login & signup** with mock Google login  
- **Email verification mock** after signup  
- **Cart system** with product count badge  
- **Checkout** supporting M-Pesa, card, and cash on delivery  
- **Auto-fill name & phone** from account (editable at checkout)  
- **Order history & statuses** (Placed → Confirmed → Shipping → Received)  
- **Reviews with images** after delivery  
- **Account management** (update details, password reset, shipping addresses)  
- Sticky footer with **muted admin login link**  

### 🛒 Admin Panel  
- Separate **restricted login**  
- Dashboard with **4 tabs**:  
  - **Inventory**: add, edit, update products, apply discounts  
  - **Orders**: update status, send customer messages  
  - **Sales**: view reports  
  - **Receipts**: generate POS receipts (print-friendly)  
- File uploads or image URLs for products  

---

## 🛠️ Tech Stack  

- **HTML5** – semantic structure  
- **CSS3** – responsive, navy blue theme, sticky footer  
- **JavaScript (ES6)** – cart, forms, interactivity  
- **Mock Payment** – M-Pesa and card checkout UI (placeholders, not live)  

---

## 🚀 Deployment  

This site is deployed on:  

- [Vercel]([https://vercel.com/](https://transcendent-biscuit-d3c0e5.netlify.app/)  

---

## 📱 Responsiveness  

- Mobile-first CSS layout  
- Scales across phones, tablets, desktops  
- Sticky footer always stays at bottom  

---

## 🧑‍💻 Author  

**Clement Kiptoo**  
📍 Kapsabet  

---

## ✅ Outcome  

- Multipage, responsive, interactive website  
- Clean project structure with separate folders (`/css`, `/js`, `/admin`, `/images`)  
- Customer and admin workflows implemented  
- Deployed with *https://transcendent-biscuit-d3c0e5.netlify.app/*
