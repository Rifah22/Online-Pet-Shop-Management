# 🐾 Online Pet Shop Management

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
</p>

> A web-based pet shop management system that allows customers to browse pets & products, book vet appointments, and place orders — with a full admin backend.

---

## 📌 Table of Contents
- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
- [Database Setup](#database-setup)

---

## 📖 About

Online Pet Shop Management is a software engineering project that simulates a real-world pet shop platform. It supports multiple user roles: customers can browse and order pet products, while admins manage the full inventory and orders. The system was designed with a focus on clean UI, role-based access, and proper database management.

---

## ✨ Features

### 👤 Customer
- User registration and login
- Browse available pets and pet products
- Add items to cart and place orders
- Book veterinary appointments
- View order history and profile

### 🛠️ Admin
- Dashboard to manage all orders
- Add, update, and delete products/pets
- Manage user accounts
- View appointment bookings

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | PHP (Native) |
| Database | MySQL |
| Server | Apache (XAMPP/WAMP) |

---

## 📸 Screenshots

> _Add screenshots of the home page, product listing, and admin dashboard here_

<!-- 
![Home Page](screenshots/home.png)
![Admin Dashboard](screenshots/admin.png)
-->

---

## ⚙️ Getting Started

### Prerequisites
- XAMPP or WAMP installed
- PHP 7.4+
- MySQL 5.7+

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Rifah22/Online-Pet-Shop-Management.git
   ```

2. **Move to server directory**
   ```bash
   # XAMPP users:
   mv Online-Pet-Shop-Management /xampp/htdocs/
   ```

3. **Start Apache and MySQL** in XAMPP Control Panel

4. **Set up the database** (see below)

5. **Open in browser**
   ```
   http://localhost/Online-Pet-Shop-Management/
   ```

---

## 🗄️ Database Setup

1. Open **phpMyAdmin** → `http://localhost/phpmyadmin`
2. Create a database named `petshop_db`
3. Import the SQL file from the repo
4. Update DB config in your connection file:
   ```php
   $host = "localhost";
   $user = "root";
   $password = "";
   $database = "petshop_db";
   ```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

---

## 👩‍💻 Author

**Rifah Sanzida**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/rifah-sanzida-b58141290/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github)](https://github.com/Rifah22)
