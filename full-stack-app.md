# Full‑Stack Blog Platform

**Status:** Live in production – 1.5 years  
**Visitors:** 1500+  
**Role:** Solo Developer (Full Stack)

---

## Overview

A complete blog platform with user accounts, Google login, comments, likes, admin controls, and visitor analytics. Built from scratch and deployed to production on a Raspberry Pi behind Cloudflare.

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | Next.js 14, React Query, Zustand, Tailwind, shadcn/ui |
| **Backend** | Node.js, Express, TypeScript, JWT, OAuth (PKCE) |
| **Database** | PostgreSQL, Drizzle ORM |
| **Deployment** | Vercel (FE), Raspberry Pi (BE), Cloudflare |

---

## Features

- 🔐 JWT Auth with silent token refresh
- 🔑 Google OAuth with PKCE (only works in local host because I use reverse proxy provided by Cloudflare that inject info to authentication header)
- 👑 Role‑based access (Admin, Editor, User)
- 💬 Comment system with likes
- 📝 Blog post management (publish/unpublish)
- 📊 Visitor analytics
- 🌙 Dark/Light theme
- ⏱️ Session management (auto‑logout on inactivity)

---

## Architecture Diagram

[UML Diagram](full-stack-app-uml.md)

---

## Live Demo

🌐 [https://your-fullstack-app.com](https://oocak.com)

---

## 📂 Related Links

- [GitHub Profile](../README.md)
- [Mobile App](https://apps.apple.com/app/your-app-id)
- [LinkedIn](https://linkedin.com/in/yourprofile)
