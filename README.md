> [!NOTE]
> **Project Status:** Version 2.0 is currently in active development. Check the roadmap below for upcoming features!

# 📋 TaskMaster Full-Stack App (v2.0) — Documentation Hub

Welcome to the central documentation and project overview for **TaskMaster (v2.0)**, a full-stack web application built as a milestone project following the completion of my military service. 

This repository serves as the master documentation hub, outlining the architecture, features, and evolution of the application from its initial front-end prototype (`v1.0`) to a fully persistent, secure full-stack system (`v2.0`).

---

## 🔄 Project Evolution: v1.0 vs. v2.0

| Feature Area | Version 1.0 (Frontend Only) | Version 2.0 (Full-Stack Architecture) |
| :--- | :--- | :--- |
| **Data Storage** | Browser `LocalStorage` with a daily reset strategy. | Persistent **MySQL Database** for reliable multi-day storage. |
| **Authentication** | Client-side mock validation and sign-up constraints. | Server-side validation, **bcrypt** password hashing, and **JWT** security. |
| **Task Management** | Daily tasks only with real-time state management. | Expanded **Daily, Weekly, and Monthly** task management via DB interaction. |
| **UI/UX Design** | Mobile-first drawer navigation (responsive SPA). | Expanded responsiveness, optimized for both mobile devices and **large desktop screens**. |

---

## ✨ Core Features & Functionality (v2.0)

### 🔐 Authentication & User Management
* [x] **Secure Sign-Up & Login:** New user data is securely stored in the database with encrypted credentials.
* [x] **Token-Based Security:** Uses **JWT (JSON Web Tokens)** and **bcrypt** for protected routing and password hashing.
* [x] **Profile Updates:** Real-time state management for updating user connection data.

### 📝 Advanced Task Management
* [x] **Flexible Time Periods:** Organize and view tasks across **Daily, Weekly, and Monthly** intervals.
* [ ] **Status Controls:** Real-time state management for creating, completing, and deleting tasks.
* [ ] **Selective Updates:** Ability to update task details for items currently *In Progress*.
* [x] **Categorization & Priorities:** Create, update, and delete custom task categories alongside a dedicated priority view for better workflow management.
* [x] **Analytics:** Visual statistics tracking task completion and productivity.

---

## 🏗️ System Architecture & Repositories

The project is structured following a modular multi-repo approach:

* [x] **TaskMaster Frontend** — Built with **React.js, JavaScript (ES6+), and React Router** (Hosted on GitHub Pages).
* [ ] **TaskMaster Backend** — Built with **Node.js, Express.js**, handling RESTful endpoints, authentication, and database connections. Link:https://github.com/GiorgosDen/ToDOListv2BackEnd
* [ ] **Database (MySQL)** — Relational database schema designed for users, tasks, categories, and states.

---

## 🗺️ Roadmap (Upcoming v3.0 Features)

- [ ] **User Groups:** Collaborative group tasks and team-based workspaces.
- [ ] **Hierarchy:** Task and team level structures.
- [ ] **Advanced Statistics:** Atomic (individual) and group-level performance statistics.

---
*Developed by Giorgos Den.*
