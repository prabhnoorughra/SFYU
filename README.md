# STEM Fellowship @ YorkU

A three-part web platform for STEM Fellowship @ YorkU:
- **Public site** for students to learn about the club and apply to join
- **Admin dashboard** for reviewing applications and basic analytics regarding the public site
- **Backend API** powering auth, applications, and page view counters

---

## Repositories

- **Frontend (Public Site)** — React + Tailwind + DaisyUI  
  👉 https://github.com/prabhnoorughra/SFYU-main-site

- **Admin Dashboard** — React + Bootstrap + JWT Auth  
  👉 https://github.com/prabhnoorughra/SFYU-admin-dashboard

- **Backend API** — Node.js + Express + Prisma + PostgreSQL  
  👉 https://github.com/prabhnoorughra/SFYU-backend

---
## Feature Highlights

### Public Site
- Mobile-first UI with Tailwind + DaisyUI
- Application form (first/last name, email, student ID, program, study year, email consent)
- Tailwind Typography for rich content pages (home/events)
- DaisyUI carousel for event galleries

### Admin Dashboard
- Secure admin login (JWT)
- Applicants table with **search**, **filters** (study year, email consent), **pagination**
- Total applicant count and basic page-view analytics
- Clean, accessible UI components

### Backend API
- Auth endpoints (standard + admin gate)
- Application CRUD (create + list with search & filters)
- **Study year** enum pattern (`First`, `Second`, `Third`, `Fourth`, `Fifth+`)
- Page view counters via an upsert pattern
- Input validation with `express-validator`

---

## TL;DR (What this does)
- Students submit an application (validated on server, persisted in Postgres).
- Admins log in, search/filter applicants (by name, study year, consent), and view pagination.
- Basic analytics: page-view counters and total application count.

