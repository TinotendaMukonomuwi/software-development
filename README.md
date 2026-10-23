# 🚴 Bicycle Rental System – Django REST Framework

This project is a backend API for a **Bicycle Rental System**, built using **Django** and **Django REST Framework (DRF)**.  
Users can register, log in, rent bicycles, return them, and view their rental history.  
Admins can manage bicycles and view all rentals through the Django admin panel.

---

## ⭐ Features

### 👤 User Features
- User registration
- Login using JWT (JSON Web Token)
- View list of bicycles
- Rent a bicycle
- Return a bicycle
- View own rental history

### 🔐 Admin Features
- Add bicycles
- Remove bicycles
- Full rental overview in admin panel

### 🧩 System Features
- JWT Authentication
- Session Authentication for DRF web UI
- REST API architecture
- Layered architecture (Models → Serializers → Views)
- SQLite database by default (easy setup)
- Can be upgraded to PostgreSQL + Docker

---

## 📁 Project Structure

PythonProject/
├── .venv/
│
├── bikernet/
│   ├── bikernet/        
│   │   ├── __init__.py
│   │   ├── asgi.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   │
│   ├── rentals/          Django-REST
│   │   ├── migrations/
│   │   │   ├── __init__.py
│   │   │   └── ... (migrations)
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── permissions.py
│   │   ├── serializers.py
│   │   ├── tests.py
│   │   ├── urls.py
│   │   └── views.py
│   │
│   ├── db.sqlite3
│   └── manage.py
│
└── README.md

