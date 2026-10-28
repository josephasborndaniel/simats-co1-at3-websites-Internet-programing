# SIMATS University Information Portal
## Five Interactive Case Study Websites for Internet Programming (CSA4315)

**Institution:** SIMATS Engineering  
**Student Name:** Joseph Asborn Daniel J  
**Register Number:** 192324009  
**Course:** Internet Programming  
**Course Code:** CSA4315  
**Assessment:** CO1 – Assessment Tool 3  
**Project:** SIMATS University Information Portal  

---

## 📌 Overview

This project implements **five standalone, highly interactive, production-ready web applications** and a central navigation portal hub designed for academic demonstration of Internet Programming concepts (client-server architecture, HTTP request-response, network protocols, DNS resolution, LAMP/WAMP stacks, HTTPS security, and web performance).

All websites are constructed using strict **HTML5, CSS3, and Vanilla JavaScript** without any external frameworks, backend runtimes, or database engines. Persistent interactive states are powered seamlessly by `localStorage`.

---

## 🌐 Case Study Websites Directory

| Website | Case Study | Key Focus Areas | Directory Path |
| :--- | :--- | :--- | :--- |
| **0. Portal Hub** | Master Index | Overview, quick-launch grid, case study breakdown | `./index.html` |
| **1. College Information Portal** | CS 31 | LAMP Architecture, HTTP Lifecycle, Faculty Search, Events | `./college-portal/index.html` |
| **2. Library Management System** | CS 32 | WAMP Stack, Port 80/8080 Troubleshooting, Issue/Return Catalogue | `./library-management/index.html` |
| **3. Examination & Results Portal** | CS 33 & 36 | Student Auth, GPA/CGPA Calc, HTTP Status Codes (404/500), TTFB/FCP Monitor | `./examination-portal/index.html` |
| **4. Secure Campus Store** | CS 34 | E-Commerce, Cart/Checkout, TLS/HTTPS Handshake, MITM vs Cipher Demo | `./campus-store/index.html` |
| **5. Administration & Network Portal** | CS 35, 37–40 | Student ERP, DNS Resolver Simulator, Network Topologies, SMTP/SFTP Debugger | `./university-admin/index.html` |

---

## 🚀 Quick Start (Local Run)

No build tools or web servers are required. Simply open `index.html` directly in any modern web browser:

1. Navigate to:
   ```
   C:\Users\HP\.gemini\antigravity-ide\scratch\simats-co1-at3-websites
   ```
2. Double-click `index.html` (or right-click -> "Open with" -> Google Chrome / Microsoft Edge / Firefox).
3. Alternatively, launch via Python or Node local HTTP server:
   ```powershell
   # Using Python
   python -m http.server 8000

   # Or using Node
   npx serve .
   ```
   Then open `http://localhost:8000` in your browser.

---

## 🛠️ Step-by-Step GitHub & Vercel Publishing Guide

### 1. Push to GitHub
1. Create a new repository on your GitHub account (e.g. `simats-co1-at3-websites`).
2. Run the following commands in PowerShell inside this directory:
   ```powershell
   cd C:\Users\HP\.gemini\antigravity-ide\scratch\simats-co1-at3-websites
   git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/simats-co1-at3-websites.git
   git branch -M main
   git push -u origin main
   ```

### 2. Deploy on Vercel
1. Log in to [vercel.com](https://vercel.com).
2. Click **Add New...** -> **Project**.
3. Import the `simats-co1-at3-websites` GitHub repository.
4. Leave all build settings at default (`Framework Preset: Other`, Root Directory: `./`).
5. Click **Deploy**. Your portal and all five websites will be live with full HTTPS!

---

## 🧪 Verification & Testing Results

- **HTML5 Validation**: Passed semantic hierarchy tests (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
- **JavaScript Syntax**: 100% verified using Node `vm` script compiler across all 5 applications.
- **Cross-Navigation**: All sub-pages include reciprocal `← Back to Portal Home` breadcrumb links to `./index.html`.
- **LocalStorage Data Persistence**: Books issued, store cart items, and registered student records correctly serialize to and retrieve from browser storage without errors.
- **Responsive Layout**: Fluid breakpoints tested across Mobile (360px), Tablet (768px), and Desktop (1280px+).

---

*Submitted by **Joseph Asborn Daniel J** (Reg No: **192324009**) for CSA4315 Internet Programming CO1 Assessment Tool 3 — SIMATS Engineering.*
