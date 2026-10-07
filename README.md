<div align="center">

# 🚀 Freelancer & Creative Agency Portfolio — Next.js 16

<p align="center">
  <strong>High-converting, agency-grade portfolio template engineered with Next.js 16 App Router, Tailwind CSS v4, and GSAP micro-animations for digital creators, freelance consultants, and studios.</strong>
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-key-features">Key Features</a> •
  <a href="#-tech-stack--architecture">Tech Stack</a> •
  <a href="#-project-structure">Project Structure</a> •
  <a href="#-getting-started">Getting Started</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Category-Design%20%26%20Portfolio%20Showcases-db2777?style=for-the-badge" alt="Category: Design & Portfolio Showcases" />
  <img src="https://img.shields.io/badge/Tech%20Stack-Next.js%20%7C%20TypeScript%20%7C%20Tailwind%20CSS-10b981?style=for-the-badge" alt="Tech Stack: Next.js | TypeScript | Tailwind CSS" />
  <img src="https://img.shields.io/badge/Status-Production%20Ready-8b5cf6?style=for-the-badge" alt="Status: Production Ready" />
  <img src="https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge" alt="License: MIT" />
</p>

</div>

---

## 📌 Overview

**Freelancer-Agency-Portfolio-NextJS** is a modern, modular digital portfolio designed to elevate client trust and drive contract inquiries. It highlights agency offerings, delivered case studies, client testimonials, and clear call-to-actions, accompanied by fluid GSAP entrance animations and responsive typography.

---

## ✨ Key Features

- 💼 **Case Studies & Project Showcase**: Dynamic portfolio display powered by structured TypeScript datasets (`data/projects.ts`).
- 🛠️ **Service Offerings & Deliverables**: Interactive service tier cards detailing scope, execution deliverables, and tech capabilities.
- 💬 **Client Testimonials & Social Proof**: Social validation sections establishing credibility and client results.
- ⚡ **GSAP Kinetic Animations**: Engaging scroll transitions and hover interactions crafted with GreenSock (GSAP 3).
- 📱 **Tailwind CSS v4 Engine**: Cutting-edge utility styling with high-performance CSS compilation and zero runtime overhead.
- 📬 **Interactive Lead Capture Form**: Clean contact section for lead acquisition and project discovery calls.

---

## 🛠️ Tech Stack & Architecture

| Layer | Technologies |
|---|---|
| **Core Framework** | Next.js 16 (App Router), React 19, TypeScript |
| **Styling & CSS** | Tailwind CSS v4, `@tailwindcss/postcss` |
| **Animation Library** | GreenSock Animation Platform (GSAP 3) |
| **Code Quality** | ESLint 9, TypeScript Strict Mode |

---

## 📂 Project Structure

```text
Freelancer-Agency-Portfolio-NextJS/
├── app/
│   ├── layout.tsx             # Root HTML layout & fonts
│   ├── page.tsx               # Main landing page orchestrator
│   └── globals.css            # Tailwind & global styles
├── components/
│   ├── Navbar.tsx             # Sticky responsive navigation
│   ├── Hero.tsx               # Bold agency headline & CTA buttons
│   ├── Services.tsx           # Agency competencies & tiers
│   ├── Projects.tsx           # Portfolio work grid with filters
│   ├── Testimonials.tsx       # Client reviews & ratings
│   ├── Contact.tsx            # Lead generation form
│   └── Footer.tsx             # Social links & copyright
├── data/
│   ├── projects.ts            # Project case study data
│   └── services.ts            # Service definitions
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18+)

### Installation & Run

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start the local development server**:
   ```bash
   npm run dev
   ```

3. **Open the browser**:
   Navigate to `http://localhost:3000`.

4. **Production Build**:
   ```bash
   npm run build
   npm run start
   ```

---

## 👤 Author
- **Nikhil** ([GitHub](https://github.com/nikhilcodeworks))

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.
