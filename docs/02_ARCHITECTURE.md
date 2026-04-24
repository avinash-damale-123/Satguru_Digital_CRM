# System Architecture – Satguru CRM

## Tech Stack

Frontend:
- Next.js (React)

Backend:
- Next.js API routes

Database:
- PostgreSQL (Supabase recommended)

Hosting:
- Vercel

Authentication:
- JWT / Supabase Auth

---

## Core System Structure

Region → Branch → Department → Role → User

---

## Data Flow

User → Lead → Activity → Conversion → Customer → Booking

---

## Module Interaction

- Lead is entry point
- Activity linked to Lead or Customer
- Customer created from Lead
- Booking created from Customer

---

## Deployment Flow

- Code stored in GitHub
- GitHub connected to Vercel
- Every push = automatic deployment
- Preview link generated

---

## Design Principle

- Modular architecture
- Clean separation of modules
- API-driven backend
- Scalable structure
