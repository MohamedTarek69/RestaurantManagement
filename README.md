<h1 align="center">🍽️ Restaurant Management System API</h1>

<p align="center">
  <b>ASP.NET Core Web API | Entity Framework Core | SQL Server</b>
</p>

<p align="center">
  A comprehensive restaurant management platform that enables customers, restaurant managers, and administrators to manage reservations, orders, menus, payments, and reviews through a secure RESTful API.
</p>

---

## 🏗️ Project Overview

The Restaurant Management System provides a complete digital solution for restaurant operations.

The system supports:

- User Authentication & Authorization
- Restaurant Management
- Menu Management
- Table Reservation System
- Order Processing
- Payment Integration
- Review System
- Real-Time Chat
- Multi-Role Access Control

---

## 👥 User Roles

### 👨‍💼 Administrator

- Manage users
- Approve restaurants
- Manage food categories
- View all orders
- View all reservations
- Manage restaurant reviews

### 🏪 Restaurant Manager

- Create and manage restaurants
- Manage menu items
- Manage tables
- Manage reservation slots
- Process customer orders
- Monitor restaurant reviews

### 👤 Customer

- Browse restaurants
- View menus
- Create orders
- Make reservations
- Submit reviews
- Manage personal orders

---

## ✨ Main Features

| Module | Description |
|----------|-------------|
| 🔐 Authentication | Register, Login, Password Reset |
| 🍽️ Restaurant Management | Create, update and approve restaurants |
| 📋 Menu Management | Full CRUD for menu items |
| 🪑 Reservation System | Table booking and timeslot management |
| 🛒 Order Management | Create and track restaurant orders |
| 💳 Payment Gateway | Stripe Checkout Integration |
| 💬 Real-Time Chat | User conversations and messaging |
| ⭐ Reviews & Ratings | Restaurant feedback system |
| 👥 Role Management | Admin, Manager, and Customer permissions |

---

## 🧱 Architecture

The project follows a layered architecture:

```text
Presentation Layer
│
├── Controllers
│
Business Layer
│
├── Services
│
Data Access Layer
│
├── Entity Framework Core
│
Database Layer
│
└── SQL Server
```

---

## 🧰 Tech Stack

| Category | Technology |
|-----------|-------------|
| Backend | ASP.NET Core Web API |
| ORM | Entity Framework Core |
| Database | SQL Server |
| Authentication | ASP.NET Identity + JWT |
| Payments | Stripe |
| Documentation | Swagger |
| Mapping | AutoMapper |
| Architecture | Repository Pattern, Dependency Injection |
| Real-Time Communication | Chat System |
| Version Control | Git & GitHub |

---

## 🔐 Authentication Features

- User Registration
- User Login
- Forgot Password
- Reset Password
- Change Password
- JWT Authentication
- Role-Based Authorization

---

## 🍽️ Restaurant Features

### Restaurant Management

- Create Restaurant
- Update Restaurant
- Delete Restaurant
- Approve / Reject Restaurant
- View Restaurant Details

### Menu Management

- Create Menu Items
- Update Menu Items
- Delete Menu Items
- Categorize Food Items

### Reservation Management

- Create Reservations
- Accept Reservations
- Reject Reservations
- Manage Time Slots
- Manage Tables

### Order Management

- Create Orders
- Update Order Status
- Cancel Orders
- Manage Order Items

---

## 💳 Payment Integration

Stripe Checkout Integration:

- Create Checkout Session
- Payment Success Handling
- Payment Cancellation Handling

---

## 💬 Chat System

- User Conversations
- Real-Time Messaging
- Conversation History

---

## ⭐ Review System

- Create Reviews
- View Restaurant Reviews
- Customer Feedback Management

---

## 🗄️ Core Entities

### Authentication

- ApplicationUser

### Restaurant Domain

- Restaurant
- MenuItem
- FoodCategory

### Reservation Domain

- Reservation
- Table
- TimeSlot

### Order Domain

- Order
- OrderItem

### Communication

- ChatMessage

### Reviews

- Review

---

## 🧠 Key Concepts

- 🔐 JWT Authentication
- 👥 Role-Based Authorization
- 💳 Stripe Payment Gateway
- 📦 Repository Pattern
- 💉 Dependency Injection
- 🔄 AutoMapper
- 📑 Swagger Documentation
- 🗃️ Entity Framework Core
- 🚀 RESTful API Design

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone <repository-url>
```

### Configure Database

Update:

```json
appsettings.json
```

### Apply Migrations

```powershell
Update-Database
```

### Run Application

```bash
dotnet run
```

---

## 📌 Future Enhancements

- Docker Support
- Microservices Architecture
- Email Notifications
- Push Notifications
- Advanced Analytics Dashboard
- Cloud Deployment

---

## 👨‍💻 Authors

<table>
<tr>
<td align="center">
<a href="https://github.com/MohamedTarek69">
<img src="https://github.com/MohamedTarek69.png" width="100px;" alt="Mohamed Tarek"/>
<br />
<b>Mohamed Tarek</b>
</a>
</td>

<td align="center">
<a href="https://github.com/Mohamedabdo273">
<img src="https://github.com/Mohamedabdo273.png" width="100px;" alt="Mohamed Abdo"/>
<br />
<b>Mohamed Abdo</b>
</a>
</td>
</tr>
</table>

---
