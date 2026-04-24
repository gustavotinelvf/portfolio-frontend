# 🚀 Portfolio Frontend - Gustavo Tínel

The frontend of a dynamic full-stack portfolio platform, built with React and Vite. Displays projects fetched from a REST API and includes a secure admin dashboard for real-time project management.

🔗 **Live Demo:** [portfolio-gustavo-tinel.vercel.app](https://portfolio-gustavo-tinel.vercel.app)
🔗 **Backend Repository:** [github.com/gustavotinelvf/portfolio-backend](https://github.com/gustavotinelvf/portfolio-backend)

---

## 📋 Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Deployment](#deployment)

---

## Overview

A responsive single-page application built with React and Vite. The public side displays projects dynamically fetched from the Spring Boot backend. An admin dashboard protected by JWT authentication allows the owner to create, edit, and delete projects in real time.

---

## 🛠️ Tech Stack

- React 18 + Vite
- Axios (with JWT interceptor)
- React Router DOM
- CSS Modules

---

## ✨ Features

- **Public Portfolio** — visitors can browse and search projects by title, language, or type
- **Secure Admin Dashboard** — JWT-protected CRUD operations for managing projects
- **Dynamic Categories** — projects categorized by programming language and application type
- **Responsive Design** — mobile-friendly layout with custom CSS

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+

### Installation

```bash
npm install
npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:

| Variable | Description |
|----------|-------------|
| `VITE_API_URL` | Backend base URL (e.g. `https://your-backend.onrender.com`) |

---

## ☁️ Deployment

Deployed on **Vercel**:
- Framework: Vite (auto-detected)
- Build command: `npm run build`
- Output directory: `dist`
- `vercel.json` configured to redirect all routes to `index.html` for React Router support

---

## 👨‍💻 Author

**Gustavo Tínel**
- LinkedIn: [linkedin.com/in/gustavotinel](https://linkedin.com/in/gustavotinel)
- GitHub: [github.com/gustavotinelvf](https://github.com/gustavotinelvf)

---

*Developed with ☕ and code*
