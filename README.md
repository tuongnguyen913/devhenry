
# 🚀 Dev Nguyen Portfolio System

> A modern, scalable, and minimal portfolio system built with cutting-edge web technologies.
> *Một hệ thống portfolio hiện đại, tối giản và có khả năng mở rộng dành cho lập trình viên.*

---

## 📌 Overview

This project is a **full-stack portfolio platform** designed to:

* Showcase personal profile, skills, and experience
* Display projects and achievements
* Provide blog/content publishing
* Support future monetization (marketplace & services)
* Separate **Public Portfolio (Anonymous)** and **Admin CMS**

> Hệ thống được thiết kế tách biệt giữa trang hiển thị công khai và hệ thống quản trị nội dung.

---

## 🏗️ Architecture

```bash
[ Next.js Portfolio (Public) ]
[ Next.js Admin CMS ]

            ↓

[ Backend API (.NET / Node.js) ]

            ↓

[ Database (SQL Server / PostgreSQL) ]

            ↓

[ Storage (Cloudinary / S3) ]
```

---

## ⚙️ Tech Stack

### Frontend

* **Next.js** (SSR, SEO optimized)
* **shadcn/ui** (UI components)
* TailwindCSS
* Framer Motion (animation)

### Backend

* ASP.NET Core Web API *(recommended based on system design experience)*
* Authentication (JWT / OAuth)

### Deployment

* **Vercel** (Frontend hosting)
* VPS / Cloud (Backend)
* Future scaling:

  * **Cloudflare**
  * **AWS**

---

## 🎯 Features

### ✅ MVP (V1)

* Personal Information
* Skills & Tech Stack
* Projects Portfolio
* Work Experience
* Blog / Articles
* Certificates & Activities
* Contact Form

### ⚙️ V2 (CMS)

* Admin dashboard
* Content management (CRUD)
* Media upload
* SEO management

### 🚀 V3 (Future)

* Marketplace (sell services/products)
* Payment integration:

  * MoMo
  * VNPay
  * PayPal

---

## 🎨 Design Philosophy

* Minimal & clean UI
* Focus on **content over decoration**
* Strong typography
* Smooth animation (non-distracting)
* Fully responsive (Desktop / Tablet / Mobile)

---

## 🌐 SEO Strategy

* Server-side rendering (SSR)
* Dynamic metadata
* Sitemap.xml & robots.txt
* Bilingual content (EN + VI)

---

# 🔥 Key Design Decisions

* Separate **Public & Admin system**
* API-driven architecture
* Scalable DB (support future SaaS/Marketplace)
* Clean, minimal UI for better UX

---

# 📈 Future Roadmap

* AI-generated content assistant
* Analytics dashboard
* Multi-language support
* Portfolio as SaaS platform

---

# 👨‍💻 Author

**Dev Nguyen Studio (DNS)**
Fullstack Developer (.NET + Angular + Next.js)
