# 👨‍💻 Anurag Sharma — Full-Stack Developer

<p align="left">
  <img src="https://img.shields.io/badge/Specialization-MERN%20Full--Stack-blue?style=flat-square" alt="Focus"/>
  <img src="https://img.shields.io/badge/Experience-5%2B%20Freelance%20Projects-brightgreen?style=flat-square" alt="Projects"/>
  <img src="https://img.shields.io/badge/Portfolio-ianuragsharma.me-purple?style=flat-square" alt="Portfolio"/>
  <img src="https://img.shields.io/badge/Status-Available%20for%20Work-success?style=flat-square" alt="Status"/>
</p>

Hi, I'm **Anurag Sharma**, a Computer Science Engineering student and **Full-Stack Developer** with hands-on experience building and deploying **5+ freelance full-stack projects** using the MERN stack and modern web technologies.

I specialize in developing **responsive, scalable, and production-ready web applications**, covering frontend development, backend APIs, database integration, authentication, payment systems, admin dashboards, and deployment.

---

## 💼 Freelancing Experience

I have worked on **5+ freelance projects** for businesses and educational organizations, handling projects from **requirements and UI development to backend APIs, database integration, deployment, and maintenance**.

### 🚀 Selected Freelance Projects

| Project | Tech Stack | Key Work | Links |
| :--- | :--- | :--- | :---: |
| 🛒 **Livique**<br/><sub>E-Commerce Platform</sub> | `React.js` `Node.js` `Express.js`<br/>`MongoDB` `JWT` `Razorpay` `Cloudinary` | Full-stack e-commerce platform, REST APIs, RBAC, cart, payments, admin dashboard, orders, users, revenue & live chat | [Live](#) • [GitHub](#) |
| 🎓 **Indo-Canadian Platform**<br/><sub>English Learning Portal</sub> | `React.js` `Google Sheets`<br/>`Apps Script` `Cloudinary` | IELTS, PTE, CELPIP, Communication & Phonics courses, enrollment system, automated emails, admin panel, deployment | [Live](#) • [GitHub](#) |
| 🏫 **Blueberry Fields School**<br/><sub>Institutional Portal</sub> | `React.js` `Node.js`<br/>`Express.js` `MongoDB` | School portal, admissions, reviews, contact/feedback forms, Google Maps, responsive UI & admin panel | [Live](#) • [GitHub](#) |
| 🍱 **QuickBites**<br/><sub>Homemade Food Delivery</sub> | `React.js` `Node.js`<br/>`Express.js` `MongoDB` `Razorpay` | Food listings, cart, checkout, payments, order workflow, authentication, image management & delivery features | [Live](#) • [GitHub](#) |
| ⚖️ **Chanakya AI**<br/><sub>Legal Assistant</sub> | `React.js` `Node.js`<br/>`LangChain` `Pinecone` `RAG` | AI-powered multilingual legal assistant with contextual retrieval, semantic search and RAG-based response generation | [Live](#) • [GitHub](#) |

<details>
<summary><b>🧑‍💻 View Core Freelancing Responsibilities (Click to Expand)</b></summary>
<br/>

* Designed and developed responsive **frontend interfaces** using React.js and Tailwind CSS.
* Built **RESTful APIs and backend services** using Node.js and Express.js.
* Designed and integrated **MongoDB/MySQL databases** for real-world applications.
* Implemented **JWT authentication, bcrypt password hashing, and Role-Based Access Control**.
* Integrated third-party services including **Razorpay, Cloudinary, Google Sheets, Apps Script, and email services**.
* Developed custom **admin dashboards** for managing products, users, orders, content, and business data.
* Tested and debugged APIs using **Postman**.
* Managed **DNS, SSL, hosting, deployment, and production configuration**.
* Worked with real client requirements and delivered complete **end-to-end web solutions**.
</details>

---

## 🛍️ Featured Project — E-Commerce Platform

> A production-oriented **full-stack e-commerce platform developed as a freelancing project**, designed to handle the complete online shopping workflow from product discovery and cart management to secure payment and order processing.

The platform includes **product management, user authentication, shopping cart, checkout, Razorpay payments, order processing, role-based access control, image management, and an admin dashboard**. It follows a **client-server architecture**, with React.js powering the frontend, Node.js and Express.js handling backend services, and MongoDB storing application data.

### ✨ Core Features

<table>
  <tr>
    <th width="50%">👤 Customer Features</th>
    <th width="50%">⚙️ Admin Features</th>
  </tr>
  <tr>
    <td valign="top">
      <ul>
        <li>Secure registration and login</li>
        <li>JWT-based authentication</li>
        <li>Product browsing, search & categories</li>
        <li>Shopping cart & quantity management</li>
        <li>Razorpay online payments & checkout</li>
        <li>Order placement, history & status tracking</li>
        <li>Responsive mobile-friendly UI</li>
      </ul>
    </td>
    <td valign="top">
      <ul>
        <li>Centralized admin dashboard</li>
        <li>Product & Category CRUD operations</li>
        <li>User and Order management</li>
        <li>Live order status updates</li>
        <li>Revenue and sales overview</li>
        <li>Cloudinary product image management</li>
        <li>Role-Based Access Control (RBAC)</li>
      </ul>
    </td>
  </tr>
</table>

### 🔄 System Architecture & Data Flows

<table>
  <tr>
    <th width="33%">🔐 Auth & Security</th>
    <th width="33%">💳 Payment Pipeline</th>
    <th width="34%">🏗️ Architecture Map</th>
  </tr>
  <tr>
    <td valign="top">
      <pre>
User Registration
      ↓
Password Hashing
      ↓
Login → JWT Token
      ↓
Protected Routes
      ↓
Role Verification
      ↓
User / Admin Access
      </pre>
      <sub>• JWT & bcrypt<br/>• Protected API endpoints<br/>• RBAC authorization</sub>
    </td>
    <td valign="top">
      <pre>
Cart → Checkout
      ↓
Create Razorpay Order
      ↓
Client Payment Gateway
      ↓
Payment Verification
      ↓
Order Confirmation
      ↓
Save to MongoDB
      </pre>
      <sub>• Backend checksum verification<br/>• Safe order dispatch</sub>
    </td>
    <td valign="top">
      <pre>
 ┌──────────────────────┐
 │   React.js Client    │
 └──────────┬───────────┘
            │ REST APIs
            ▼
 ┌──────────────────────┐
 │ Node.js + Express.js │
 └─────┬──────────┬─────┘
       ▼          ▼
 ┌──────────┐ ┌──────────┐
 │ MongoDB  │ │ Razorpay │
 └─────┬────┘ └──────────┘
       ▼
 ┌────────────┐
 │ Cloudinary │
 └────────────┘
      </pre>
    </td>
  </tr>
</table>

---

## 🧩 Technology Stack & Competencies

<table>
  <tr>
    <td width="50%">
      <b>🌐 Frontend</b><br/>
      <code>React.js</code> <code>JavaScript</code> <code>Tailwind CSS</code> <code>HTML5</code> <code>CSS3</code>
    </td>
    <td width="50%">
      <b>⚙️ Backend</b><br/>
      <code>Node.js</code> <code>Express.js</code> <code>REST APIs</code> <code>JWT</code> <code>bcrypt</code>
    </td>
  </tr>
  <tr>
    <td>
      <b>🗄️ Database & Storage</b><br/>
      <code>MongoDB</code> <code>Mongoose</code> <code>MySQL</code> <code>Firebase</code>
    </td>
    <td>
      <b>💳 Services & Payments</b><br/>
      <code>Razorpay</code> <code>Cloudinary</code> <code>Google Sheets API</code> <code>Postman</code>
    </td>
  </tr>
  <tr>
    <td>
      <b>🚀 Deployment & Versioning</b><br/>
      <code>Git</code> <code>GitHub</code> <code>Vercel</code> <code>Render</code> <code>AWS</code>
    </td>
    <td>
      <b>🧠 Core Concepts</b><br/>
      <code>Data Structures & Algorithms</code> <code>OOP</code> <code>DBMS</code> <code>OS</code> <code>Networks</code>
    </td>
  </tr>
</table>

<details>
<summary><b>⚡ View Engineering Highlights (Click to Expand)</b></summary>
<br/>

* Full-stack MERN architecture with modular code separation
* Secure JWT authentication with HTTP-only cookies / bearer token workflows
* Razorpay payment gateway integration with robust backend signature verification
* Asset optimization and dynamic CDN delivery via Cloudinary
* Scalable MongoDB schemas with indexing and relationship modeling
* Production-ready deployment setup with strict environment separation
</details>

---

## 📂 Project Structure & Setup

<details>
<summary><b>📁 Directory Structure (Click to Expand)</b></summary>

```text
ecommerce/
│
├── frontend/
│   ├── src/
│   │   ├── components/       # Reusable UI elements
│   │   ├── pages/            # Page-level route views
│   │   ├── hooks/            # Custom hooks
│   │   ├── services/         # API integration layers
│   │   ├── context/          # Context API providers
│   │   └── utils/            # Helper utilities
│   └── package.json
│
├── backend/
│   ├── controllers/          # Request handlers
│   ├── models/               # MongoDB Mongoose models
│   ├── routes/               # API endpoints
│   ├── middleware/           # Auth & error handling
│   ├── services/             # Third-party integrations
│   ├── config/               # Database & env config
│   └── server.js             # Server entry point
│
├── README.md
└── package.json