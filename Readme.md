# School Management System (Full Stack Admin Panel)

A **production-inspired, full-stack School Management System** with role-based access, an admin dashboard, secure authentication, robust CRUD operations, and real-world business logic.

---

##  Project Overview

This project is **originally based on a production-style template**, then extensively extended and customized by me to demonstrate real-world engineering skills and deep full-stack expertise.

**Key Highlights:**
* Implemented major features such as complete CRUD functionality for student management.
* Fixed and enhanced the notice board system (including bug fixes for field handling).
* Integrated and improved backend services, frontend flows, and database structure.
* Debugged and resolved critical frontend-backend integration issues, ensuring a seamless user experience across the admin panel.
* Contributed architectural improvements, followed controller/service/repository patterns, and ensured security, data validation, and best practices throughout.

---

##  Tech Stack

### Frontend
* **React.js** – Fast, interactive user interfaces
* **Vite** – Modern build tool and dev server
* **Redux Toolkit + RTK Query** – State management & API handling
* **Material-UI (MUI)** – Professional-grade UI components
* **React Hook Form** + **Zod** – Robust form handling and validation

### Backend
* **Node.js** & **Express.js** – Modular REST API server
* **MVC Architecture:** Controller, Service, Repository layers
* **Nodemon** – Auto-reloading dev server
* **Argon2** – Secure password hashing

### Database
* **PostgreSQL** – Relational DB with strong support for business logic
* **Custom SQL Scripts** – Table creation, business logic, seed data

### Other Tools
* **JWT** – Token-based authentication
* **dotenv** – Environment variable management
* **Mail Service** – Account verification

---

##  Features

* **Authentication:** JWT-based login, CSRF protection
* **Role Management:** Admin, Teacher, Student; dynamic, editable roles
* **Dashboard:** User stats, recent notices, leave summaries, celebrations
* **CRUD Operations:**
    * Students: Add, view, edit, enable/disable
    * Teachers, Staff, Departments: Full management flows
* **Leave Management:** Policies, requests, approvals
* **Notice Board:** Add/edit/manage notices, target by user group/role
* **Permissions:** Fine-grained access via roles and API guards

---

##  Architecture

* **Full-stack:** Separate frontend (React) and backend (Node/Express) communicating via REST API
* **Production-style:** Modular codebase with clear separation of concerns:
    * **Routers:** API endpoints
    * **Controllers:** HTTP logic
    * **Services:** Business logic & validation
    * **Repositories:** Database queries

---

##  Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/SahilWadhwani/school-management-system.git
cd school-management-system
````

### 2\. Setup the database

Install PostgreSQL.
Create a database and user as in your `.env` file.
Run SQL scripts in `seed_db/tables.sql` and `seed_db/seed-db.sql`.

### 3\. Backend setup

```bash
cd backend
cp .env.example .env   # Edit with your DB credentials
npm install
npm run dev
```

### 4\. Frontend setup

```bash
cd frontend
cp .env.example .env   # Edit with your API URL if needed
npm install
npm run dev
```

The app should be live at `http://localhost:5173/`.

-----

##  Why This Project?

This project showcases:

  * **Production-grade architecture:** Realistic backend and frontend structure using best industry practices.
  * **Full-stack mastery:** From UI and forms, through backend APIs, to relational data modeling.
  * **Modern tech:** Tools and patterns used by leading tech companies.
  * **Problem-solving:** Debugged and extended core features (student CRUD, notice system), implemented missing business logic, and ensured seamless operation throughout the stack.

