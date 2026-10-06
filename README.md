# 🛒 E-Commerce REST API

A production-grade e-commerce backend built with FastAPI.

## Tech Stack
- **Backend:** Python, FastAPI
- **Database:** PostgreSQL + SQLAlchemy ORM
- **Auth:** JWT (python-jose + bcrypt)
- **Architecture:** Router → Service → Repository pattern

## Features
- 🔐 JWT Authentication (register, login)
- 📦 Products — CRUD, image upload, search, pagination
- 🗂️ Categories — CRUD (admin only)
- 🛒 Cart — add, update, remove, clear
- 📋 Orders — place, track, admin status update
- 📸 File uploads — product images
- 📧 Background tasks — order confirmation email
- ⚠️ Global error handling — consistent error format
- 🔒 Role-based access — admin vs customer