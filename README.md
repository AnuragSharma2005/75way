# 👨‍💻 Anurag Sharma — Full-Stack Developer

<p align="left">
  <img src="https://img.shields.io/badge/Specialization-MERN%20Full--Stack-blue?style=flat-square" alt="Focus"/>
  <img src="https://img.shields.io/badge/Experience-5%2B%20Freelance%20Shipped-brightgreen?style=flat-square" alt="Projects"/>
  <img src="https://img.shields.io/badge/Stack-React%20%7C%20Node%20%7C%20TypeScript%20%7C%20MongoDB-orange?style=flat-square" alt="Stack"/>
  <img src="https://img.shields.io/badge/Portfolio-ianuragsharma.me-purple?style=flat-square" alt="Portfolio"/>
</p>

Hi, I'm **Anurag Sharma**, a Computer Science Engineering student and **Full-Stack Developer** with hands-on experience building and deploying **5+ freelance full-stack projects** using the MERN stack, TypeScript, and modern web technologies.

I specialize in developing **responsive, scalable, and production-ready web applications**, covering frontend architectures, backend APIs, database integration, authentication, payment systems, admin dashboards, and cloud deployment.

---

## 💼 Freelancing Experience

I have engineered **5+ freelance client solutions** across e-commerce, educational institutions, culinary platforms, and personal brands — driving architecture from SRS gathering to cloud deployment and post-launch maintenance.

### 🚀 Selected Freelance Projects

<table>
  <thead>
    <tr>
      <th width="32%">Project</th>
      <th width="40%">Tech Stack</th>
      <th width="28%">Deliverables & Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>🛒 Livique</b><br/><i>E-Commerce Platform</i></td>
      <td><code>React.js</code> <code>TypeScript</code> <code>Node.js</code> <code>Express.js</code> <code>MongoDB</code> <code>JWT</code> <code>Razorpay</code> <code>Cloudinary</code></td>
      <td>Full-stack multi-category store, RBAC, orders, live payments, admin revenue dashboard.<br/>👉 <a href="https://livique.co.in">Live Site</a> • <a href="https://github.com/AnuragSharma2005/75way">GitHub</a></td>
    </tr>
    <tr>
      <td><b>🎓 Apex Edge English</b><br/><i>Indo-Canadian Client Project</i></td>
      <td><code>React.js</code> <code>Google Sheets API</code> <code>Apps Script</code> <code>Cloudinary</code> <code>Tailwind CSS</code></td>
      <td>IELTS, PTE, CELPIP & Phonics course platform, booking automation & admin portal.<br/>👉 <a href="https://apexedgeenglish.com/">Live Site</a> • <a href="https://github.com/AnuragSharma2005/apexedgeenglish">GitHub</a></td>
    </tr>
    <tr>
      <td><b>🏫 Blueberry Fields School</b><br/><i>Institutional Web Portal</i></td>
      <td><code>React.js</code> <code>Node.js</code> <code>Express.js</code> <code>MongoDB</code> <code>Tailwind CSS</code></td>
      <td>Admissions engine, interactive feedback channels, geolocated UI & admin CMS.<br/>👉 <a href="https://blueberryfieldsschool.com/">Live Site</a> • <a href="https://github.com/Moksh-Digital/Blueberry-Fields-School">GitHub</a></td>
    </tr>
    <tr>
      <td><b>✨ Deepika Chawla</b><br/><i>Anchor & Trainer Portfolio</i></td>
      <td><code>React.js</code> <code>Tailwind CSS</code> <code>Vite</code> <code>Media Services</code></td>
      <td>High-conversion personal branding portfolio, corporate media showcase & contact funnel.<br/>👉 <a href="https://deepikashine.com/">Live Site</a> • <a href="https://github.com/AnuragSharma2005/freelancing">GitHub</a></td>
    </tr>
  </tbody>
</table>

<details>
<summary><b>🧑‍💻 View Core Freelancing Responsibilities (Click to Expand)</b></summary>
<br/>

* Designed and built responsive, mobile-first SPAs using **React.js, TypeScript, and Tailwind CSS**.
* Architected scalable **RESTful APIs and services** with Node.js and Express.js.
* Modeled high-integrity database schemas using **MongoDB / Mongoose and MySQL**.
* Implemented production-grade security: **JWT, bcrypt password hashing, CORS, and RBAC tiers**.
* Integrated critical APIs: **Razorpay payment checkout, Cloudinary media CDN, and Google Sheets automations**.
* Built dedicated **administrative control rooms** for order fulfillment, user permissions, and content updates.
* Managed DNS records, SSL handshakes, Nginx reverse-proxies, and cloud deployments on **Vercel / Render**.
</details>

---

## 🛍️ Featured Project — Livique E-Commerce Platform

> A production-oriented **full-stack e-commerce engine** built to handle complete digital retail workflows: product discovery, dynamic carts, backend checksum payments, and order tracking.

The application follows a modular **client-server architecture** with React + Vite on the presentation layer, Express/Node.js powering the API tier, and MongoDB managing structured data.

### ✨ Core Capabilities

<table>
  <tr>
    <th width="50%">👤 Customer Experience</th>
    <th width="50%">⚙️ Merchant Operations</th>
  </tr>
  <tr>
    <td valign="top">
      <ul>
        <li>Secure authentication via JWT & bcrypt</li>
        <li>Instant search with category-based filtering</li>
        <li>Real-time cart state with quantity sync</li>
        <li>Razorpay checkout & instant payment hooks</li>
        <li>Lifecycle order status tracking</li>
        <li>Fully responsive, mobile-first design</li>
      </ul>
    </td>
    <td valign="top">
      <ul>
        <li>Centralized administrative dashboard</li>
        <li>Full Product & Category CRUD interfaces</li>
        <li>Customer order records & state management</li>
        <li>Order status dispatch & shipping updates</li>
        <li>High-level store revenue & sales analytics</li>
        <li>Role-Based Access Control (Admin vs Customer)</li>
      </ul>
    </td>
  </tr>
</table>

### 🔄 System Architecture & Data Flows

<table width="100%">
  <thead>
    <tr>
      <th width="24%">🔐 Auth & Security</th>
      <th width="24%">💳 Payment Pipeline</th>
      <th width="26%">🏗️ System Mesh</th>
      <th width="26%">🚀 CI/CD & Cloud Ops</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top">
        <pre>
Client Credentials
       │
       ▼
[bcrypt Hash / Salt]
       │
       ▼
[JWT Token Signed]
       │
       ▼
Bearer Header Attach
       │
       ▼
Auth Middleware
       │
       ▼
RBAC Access Router
  ┌────┴────┐
  ▼         ▼
[Admin]   [User]
        </pre>
        <sub>• Stateless JWT session<br/>• Granular RBAC gates</sub>
      </td>
      <td valign="top">
        <pre>
Cart Checkout
       │
       ▼
Order Initiated
       │
       ▼
Razorpay SDK Window
       │
       ▼
Customer Payment
       │
       ▼
HMAC SHA-256 Sign
       │
       ▼
Database Commit
       │
       ▼
Order Dispatched
        </pre>
        <sub>• Tamper-proof webhook<br/>• Server-side checksum</sub>
      </td>
      <td valign="top">
        <pre>
┌──────────────────────┐
│  React.js + Vite UI  │
└──────────┬───────────┘
           │ HTTPS / REST
           ▼
┌──────────────────────┐
│ Node.js + Express API│
└─────┬──────────┬─────┘
      │          │
      ▼          ▼
┌───────────┐ ┌────────────┐
│  MongoDB  │ │  Razorpay  │
└─────┬─────┘ └────────────┘
      │
      ▼
┌────────────┐
│ Cloudinary │
└────────────┘
        </pre>
        <sub>• Decoupled MERN stack<br/>• Cloudinary CDN media</sub>
      </td>
      <td valign="top">
        <pre>
 git push (main)
       │
       ▼
┌──────────────────────┐
│  GitHub Repository   │
└─────┬──────────┬─────┘
      │          │
      ▼          ▼
┌───────────┐ ┌────────────┐
│  Vercel   │ │DigitalOcean│
│(Front-End)│ │  / Render  │
└───────────┘ └─────┬──────┘
                    │
                    ▼
              ┌────────────┐
              │Nginx + SSL │
              └────────────┘
        </pre>
        <sub>• Automated deployments<br/>• Nginx reverse proxy</sub>
      </td>
    </tr>
  </tbody>
</table>

## 🧩 Technology Stack & Competencies

<table width="100%">
  <tr>
    <td width="33.33%" valign="top">
      <h4>🌐 Frontend & UI</h4>
      <img src="https://img.shields.io/badge/React.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /><br/>
      <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" /><br/>
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
    </td>
    <td width="33.33%" valign="top">
      <h4>⚙️ Backend & Storage</h4>
      <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" /><br/>
      <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge" /><br/>
      <img src="https://img.shields.io/badge/JWT_Auth-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white" />
    </td>
    <td width="33.33%" valign="top">
      <h4>🚀 Cloud & Tooling</h4>
      <img src="https://img.shields.io/badge/Razorpay-02042B?style=for-the-badge&logo=razorpay&logoColor=3395FF" /><br/>
      <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
    </td>
  </tr>
</table>

> ⏳ **Live Demo Note:** The backend is currently hosted on Render's free tier (following domain/plan subscription expiry). The initial server spin-up might take around **2–3 minutes** to wake up on your first visit. Thank you for your patience! 


<details>
<summary><b>⚡ View Engineering Highlights (Click to Expand)</b></summary>
<br/>

* Full-stack MERN architecture decoupled with Vite client and Express server
* End-to-end TypeScript configurations across client and server environments
* Production Nginx reverse proxy configurations (`nginx-http.conf` & `nginx-https.conf`)
* Strict payment checksum verification prevents order manipulation
* Cloudinary asset optimization with automatic format delivery
* Standardized API testing workflows using Postman
</details>

---

## 📂 Project Structure & Setup

<details>
<summary><b>📁 Repository Layout (Click to Expand)</b></summary>

```text
75way/Livique/
│
├── 📁 backend/                        # API routes, models & controllers
├── 📁 public/                         # Static assets & icons
├── 📁 src/                            # React + TS frontend
│   ├── 📁 components/                 # UI components
│   │   ├── 📁 ui/                     # UI primitives
│   │   ├── ⚛️ Banner.tsx              # Promo banner
│   │   ├── ⚛️ Footer.tsx              # Page footer
│   │   ├── ⚛️ Header.tsx              # Navbar & search
│   │   ├── ⚛️ PushNotificationButton.tsx # Push alerts
│   │   └── ⚛️ StepsTracker.tsx         # Checkout progress
│   │
│   ├── 📁 contexts/                   # State providers
│   ├── 📁 data/                       # Mock & static data
│   ├── 📁 hooks/                      # Custom hooks
│   ├── 📁 lib/                        # Helpers & utils
│   ├── 📁 pages/                      # Page views
│   │   ├── ⚛️ About.tsx               # About page
│   │   ├── ⚛️ Address.tsx             # Address manager
│   │   ├── ⚛️ Admin.tsx               # Admin panel
│   │   ├── ⚛️ AdminQueries.tsx        # Support queries
│   │   ├── ⚛️ Cart.tsx                # Shopping cart
│   │   ├── ⚛️ Category.tsx            # Category browser
│   │   ├── ⚛️ Home.tsx                # Homepage
│   │   ├── ⚛️ Index.tsx               # Root entry
│   │   ├── ⚛️ NotFound.tsx            # 404 page
│   │   ├── ⚛️ OrderConfirmation.tsx   # Order success
│   │   ├── ⚛️ Payment.tsx             # Razorpay checkout
│   │   ├── ⚛️ ProductDetail.tsx       # Product view
│   │   ├── ⚛️ ProductList.tsx         # Catalog list
│   │   ├── ⚛️ ProfilePage.tsx         # User profile
│   │   ├── ⚛️ SearchResultsPage.tsx   # Search results
│   │   ├── ⚛️ SignIn.tsx              # Login page
│   │   └── ⚛️ SignUp.tsx              # Register page
│   │
│   ├── 📁 utils/                      # Utilities & formatters
│   ├── 🎨 App.css                     # App styles
│   ├── ⚛️ App.tsx                     # Main layout & router
│   ├── 🎨 index.css                   # Tailwind base styles
│   ├── ⚛️ main.tsx                    # Root mount
│   └── 📝 vite-env.d.ts               # Vite types
│
├── ⚙️ .gitignore
├── 📦 bun.lockb                       # Bun lockfile
├── ⚙️ components.json                 # UI config
├── ⚙️ eslint.config.js                # ESLint config
├── 📄 index.html                      # HTML entry
├── 🌐 nginx-http.conf                 # Nginx HTTP
├── 🔒 nginx-https.conf                # Nginx HTTPS
├── 📦 package-lock.json               # Lockfile
├── 📦 package.json                    # Dependencies
├── ⚙️ postcss.config.js               # PostCSS config
├── 📜 QUICK_SETUP.sh                  # Setup script
├── 📖 README.md                       # Documentation
├── ⚙️ tailwind.config.ts              # Tailwind config
├── 🧪 test-migration.js               # Migration tests
├── 🧪 test.js                         # Unit tests
├── 📝 tsconfig.app.json               # App TS config
├── 📝 tsconfig.json                   # Base TS config
├── 📝 tsconfig.node.json              # Node TS config
├── 🚀 vercel.json                     # Vercel config
└── ⚡ vite.config.ts                  # Vite config