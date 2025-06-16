# 🌐 Virtual Community Support Platform

A full-stack web application designed to connect community members with support services and resources. This platform was developed using **Angular** for the frontend, **.NET Core** for the backend API, and **PostgreSQL** for data management. Built during my internship at **TatvaSoft**.

---

## 📌 Project Overview

The **Virtual Community Support Platform** empowers users to interact, access community support, share resources, and request help — especially valuable during times of crisis (e.g., pandemic, natural disasters). Admins can manage users, services, and requests, while users can register, browse resources, and interact with the community digitally.

The system is built with a focus on **scalability**, **security**, and **modular design**, making it suitable for NGOs, local governments, or disaster relief organizations.

---

## 🚀 Key Features

### 👥 User Module
- User registration and login (JWT Authentication)
- User profile management
- Browse and request community services (e.g., food, medical help, shelter)

### 🧑‍💼 Admin Panel
- Manage users, roles, and permissions
- Approve or reject user service requests
- Manage categories of support (e.g., health, education, donations)

### 📨 Requests & Responses
- Users can post support requests
- Admins or volunteers can respond or assign requests
- Request status tracking: pending, approved, resolved

### 📢 Announcements & Notices
- Admins can post news, events, and alerts
- Visible on the homepage for all users

### 🗃️ PostgreSQL Integration
- Relational database schema for:
  - Users & roles
  - Services
  - Requests & messages
  - Notifications
- Secure, normalized, and optimized queries using Entity Framework Core

---

## 🧰 Tech Stack

| Layer        | Technology                      |
|--------------|----------------------------------|
| Frontend     | Angular (TypeScript, HTML, SCSS) |
| Backend API  | .NET Core Web API (C#)           |
| Database     | PostgreSQL                       |
| ORM          | Entity Framework Core            |
| Auth         | JWT-based Token Authentication   |
| Hosting      | IIS / Azure / Docker-Ready       |

