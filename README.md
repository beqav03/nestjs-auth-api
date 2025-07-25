# NestJS Auth API 🔐

A production-ready Authentication & Authorization microservice using NestJS.  
Supports secure user registration, login, role-based access, JWT refresh tokens, and clear API docs.

---

## 🚀 Overview

**What is this?**  
A focused backend service built with NestJS to handle user authentication, user roles, and protected endpoints.

**Why it exists:**  
It enables developers or employers to view a clean, modular Auth API example showing JWT handling, guards, secure practices, and environment settings.

---

## 🔧 Features

- ✅ User Registration & Login
- ✅ JWT Access + Refresh Token flow
- ✅ Password Hashing (bcrypt)
- ✅ Role-Based Access Control (user, admin)
- ✅ Protected routes with NestJS Guards
- ✅ Input Validation using DTOs (`class-validator`)
- ✅ Optional & Clean Swagger documentation
- ✅ Docker support for easy local setup

---

## ⚙️ Tech Stack

| Component        | Details                     |
|------------------|-----------------------------|
| Framework        | NestJS (TypeScript)         |
| Database         | PostgreSQL (TypeORM)        |
| Auth & Security  | JWT, bcrypt, Guards         |
| Docs             | Swagger (OpenAPI via Nest)  |
| Dev Tools        | Jest (unit & e2e), Docker   |

---

## 📥 Quick Start

### Prerequisites:
- Node.js ≥ 16
- PostgreSQL running (or can use a Docker container)

### Setup:
```bash
git clone https://github.com/beqav03/nestjs-auth-api.git
cd nestjs-auth-api
npm install
cp .env.example .env
# Edit .env file to set secrets and db credentials
npm run start:dev
