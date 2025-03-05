# 🛠️ LEONI IT Equipment Management System

A **Laravel + Vue.js** based application for managing IT equipment across multiple sites.

---

## 🚀 Quick Setup Guide

Follow these steps to set up the project:

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/Jasser0107/Projet-Pfe.git
cd LEONI
2️⃣ Install Dependencies
composer install
npm install
npm run dev
3️⃣ Configure Environment
Duplicate the .env.example file:

cp .env.example .env
Then, open the .env file and update the database configuration:

DB_DATABASE=leoni
DB_USERNAME=root
DB_PASSWORD=
4️⃣ Run Database Migrations

php artisan migrate
5️⃣ Seed the Database (With Test Users)

php artisan migrate --seed
6️⃣ Start the Server

php artisan serve
Now, open localhost:8000 in your browser.

📌 Test User Credentials
You can use the following test accounts to log in:

🏷️ Role	✉️ Email	🆔 Username	🔑 Password
Super Admin	admin@example.com	superadmin	password
Manager	manager@example.com	manager	password
Superior	superior@example.com	superior	password
Employee	employee@example.com	employee	password
⚠️ Note: You can modify these users in the UserSeeder.php file.

🌟 Features
✅ Role-Based Access Control (RBAC) (Super Admin, Manager, Superior, Employee)
✅ Separate Dashboards for Each Role
✅ Authentication using Laravel Breeze & Inertia.js
