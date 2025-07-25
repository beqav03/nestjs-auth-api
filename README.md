# NestJS Auth API

A robust authentication and authorization API built with NestJS.  
Supports user registration, login, role-based access, refresh tokens, and more.

## 🔐 Features

- User Registration & Login
- JWT Authentication (Access & Refresh Tokens)
- Role-based Authorization (e.g. Admin, User)
- Password Hashing (bcrypt)
- Email/Username Uniqueness Validation
- Protected Routes using Guards
- Token Refresh Endpoint
- Rate Limiting (optional)
- Fully modular structure with DTOs, services, and controllers

## 🛠 Tech Stack

- **Backend Framework**: [NestJS](https://nestjs.com/)
- **Database**: PostgreSQL / MySQL (via TypeORM)
- **Authentication**: JWT, bcrypt
- **Validation**: class-validator, class-transformer

## 📦 Installation

```bash
git clone https://github.com/yourusername/nestjs-auth-api.git
cd nestjs-auth-api
npm install
```
