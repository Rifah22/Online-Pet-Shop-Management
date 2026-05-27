# 🐾 Online Pet Shop Management

<p align="center">
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scrum-6DB33F?style=for-the-badge&logo=scrumalliance&logoColor=white"/>
  <img src="https://img.shields.io/badge/Agile-FF6F00?style=for-the-badge&logo=agile&logoColor=white"/>
  <img src="https://img.shields.io/badge/Project_Planning-0077B5?style=for-the-badge&logo=trello&logoColor=white"/>
</p>

> Agile project planning and sprint backlog documentation for an Online Pet Shop Management System — managed using Jira Scrum methodology.

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Repository Contents](#-repository-contents)
- [Planned System Features](#-planned-system-features)
- [Scrum Sprint Breakdown](#-scrum-sprint-breakdown)
- [Team](#-team)
- [Project Management](#-project-management)

---

## 📖 About the Project

**Online Pet Shop Management** is a planned full-stack web platform for managing an online pet shop. This repository contains the **Agile project planning artifacts** — including a full Jira Scrum backlog and a sprint setup guide — created as part of an SRE (Software Requirements Engineering) mid-term assignment.

The system is designed to support customers browsing and purchasing pet-related products (pets, food, accessories), while giving admins tools to manage inventory, promotions, and customer support.

> ⚠️ **Note:** This repository contains planning documentation only. The actual application source code is not yet included.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Online Pet Shop Management - Backlog - Jira.html` | Full exported Jira Scrum backlog with all sprints, epics, stories, and subtasks |
| `Online Pet Shop Management - Backlog - Jira_files.zip` | Supporting assets for the Jira HTML export |
| `SRE MID Assignment.pdf` | Step-by-step documentation of the Jira project setup (screenshots of sprint creation, board, timeline, backlog) |

---

## ✨ Planned System Features

### 👤 User (Customer)
- Register an account with email
- Secure login and authentication
- Manage profile details (name, address) for accurate delivery
- Browse products by category (Pets, Food, Accessories, etc.)
- Add items to a shopping cart and review before purchase
- Securely pay using multiple payment methods
- Track order status (e.g., Pending, Shipped, Delivered)
- Receive promotional emails for discounts and offers
- View active sales banners on the homepage
- Contact support via live chat
- Submit feedback to improve services

### 🛠️ Admin
- Add and update product listings with the latest details
- Create and manage product categories (dogs, cats, fish, etc.)
- Track inventory levels to prevent overselling
- Create and manage coupon codes to attract customers
- Manage customer accounts and orders

---

## 🗂️ Scrum Sprint Breakdown

The project was planned across **6 sprints** using Jira Scrum. Below is the full breakdown:

### 🏃 Sprint 1 — User Management *(10 Dec – 25 Dec)*
| Story | Status | Assignee |
|-------|--------|----------|
| As a user, I want to register an account with my email so I can access the platform. | ✅ Done |Md Samin Yeasar |
| As a user, I want to log in securely so that only I can access my account. | ✅ Done | Md Samin Yeasar |
| As a user, I want to manage my profile details (e.g., name, address) for accurate order delivery. | ✅ Done | Md Samin Yeasar |
| As a user, I want to track my order status (e.g., shipped, delivered) for timely updates. | 🔄 In Progress | Md Samin Yeasar |

### 🏃 Sprint 2 — Product Management *(25 Dec – 1 Jan)*
| Story | Status | Assignee |
|-------|--------|----------|
| As an admin, I want to add and update product details so users see the latest offerings. | ✅ Done | Rifah Sanzida |
| As a user, I want to browse products by categories (e.g., Pets, Food) for easier navigation. | ✅ Done | Rifah Sanzida |
| As an admin, I want to track inventory levels to prevent overselling. | 🔄 In Progress | Rifah Sanzida |

**Subtasks for Product Management epic:**
- Design the product catalog structure (categories, subcategories)
- Implement the backend for adding and updating products
- Create a UI for browsing products by category
- Implement product pagination and infinite scroll

### 🏃 Sprint 3 — Order Management *(2 Jan – 9 Jan)*
| Story | Status | Assignee |
|-------|--------|----------|
| As a user, I want to add items to a shopping cart so I can review them before purchasing. | ✅ Done | Md Samin Yeasar |
| As a user, I want to securely pay for my order using multiple payment methods. | ✅ Done | Md Samin Yeasar |

### 🏃 Sprint 4 — Marketing & Promotions *(11 Jan – 25 Jan)*
| Story | Status | Assignee |
|-------|--------|----------|
| As a user, I want to receive promotional emails for discounts and offers. | ✅ Done | Rifah Sanzida |
| As an admin, I want to create and manage coupon codes to attract more customers. | ✅ Done | Rifah Sanzida |
| As a user, I want to see a banner on the homepage showcasing current sales. | 🔄 In Progress | Rifah Sanzida |

### 🏃 Sprint 5 — Customer Support *(26 Jan – 9 Feb)*
| Story | Status | Assignee |
|-------|--------|----------|
| As a user, I want to contact support through live chat to resolve issues quickly. | ✅ Done | Md Samin Yeasar |
| As a user, I want to submit feedback to help improve services. | 🔄 In Progress | Md Samin Yeasar |

### 🏃 Sprint 6 *(10 Feb – 3 Mar)*
> Sprint 6 work items are planned but not yet populated in the backlog.

---

## 👩‍💻 Team

**Rifah Sanzida** — Product Management & Marketing sprints
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rifah-sanzida-b58141290/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Rifah22)

**Md Samin Yeasar** — User Management, Order Management & Customer Support sprints
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-samin-yeasar-4986ab290/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/MdSaminYeasar)

---

## 🗃️ Project Management

This project was planned using **Jira Software** with a **Scrum framework**:

- **Epics:** User Management, Product Management, Order Management, Marketing and Promotions, Customer Support
- **Stories:** Written as user stories (`As a [role], I want to [action] so that [goal]`)
- **Subtasks:** Each story broken down into design, backend, and frontend implementation tasks
- **Sprints:** 6 time-boxed sprints with assignees and story point estimates
- **Board & Timeline:** Managed via Jira Kanban board and Gantt-style timeline view

The `SRE MID Assignment.pdf` documents the complete Jira setup process with screenshots, from project creation to sprint execution.

---

## 📄 License

This project is open source and available for educational purposes.
