# Employee Data Management System

This is a simple web-based application for managing employee data, built using HTML, CSS, PHP, and MySQL, and hosted locally using XAMPP.

---

##  Project Overview

This system allows users to:
- Add new employees (name and age)
- View employee data in a styled table
- Toggle employee status (active/inactive)

---

##  Tools & Technologies Used

- Frontend: HTML + CSS
- Backend: PHP
- Database: MySQL
- Local Server: XAMPP (Apache + MySQL)

---

##  How to Run the Project (with XAMPP)

> This project runs locally using the XAMPP environment.

### 1. Install XAMPP
- Download XAMPP from: [https://www.apachefriends.org](https://www.apachefriends.org)
- Install it on your device and open the XAMPP Control Panel

### 2. Start Apache & MySQL
- Open XAMPP Control Panel
- Start both Apache and MySQL modules

### 3. Create Database in phpMyAdmin
- Open your browser and go to:  
  http://localhost/phpmyadmin

- Create a new database named:
  employees
- Inside that database, create a table called:
  - Use the following structure:

| Column  | Type     | Attributes                     |
|---------|----------|--------------------------------|
| id      | INT      | PRIMARY KEY, AUTO_INCREMENT    |
| name    | VARCHAR  | Length: 255                    |
| age     | INT      |                                |
| status  | TINYINT  | Default: 0                     |

---

### 4. Add Project Files to htdocs
- Copy all the project files:
- index.php
- insert.php
- toggle.php
- style.css

- Paste them inside:
- C:\xampp\htdocs\employee-app

  ---

### 5. Run the Web App
- In your browser, go to:
  http://localhost/employee-app/

  
## Demo
![demo](employee-app-demo.fig)
