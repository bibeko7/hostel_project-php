# 🏠 Hostel Management System (PHP)
# Hostel name Scholars' Nest Hostel

<img width="1919" height="911" alt="image" src="https://github.com/user-attachments/assets/c04ffb68-63ee-483a-85d1-bf2083ec180d" />

## 📌 Description

This project is a **Hostel Management System** developed using PHP and MySQL.
It allows **hostel owners to list available rooms** and **students to browse and apply for rooms online**, making the process simple and efficient.

---

## 🚀 Features

### 👤 Student Side

* Student registration and login
* View available rooms
* Apply/request for rooms
* Dashboard for managing requests

### 🏢 Owner Side

* Owner registration and login
* Add new rooms
* View listed rooms
* Manage student requests/applications
* Remove or update room listings

---

## 🛠️ Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** PHP
* **Database:** MySQL

---

## 📂 Project Structure

* `/sreg.php` → Student registration
* `/slog.php` → Student login
* `/sdash.php` → Student dashboard
* `/oreg.php` → Owner registration
* `/olog.php` → Owner login
* `/odash.php` → Owner dashboard
* `/showrooms.php` → View rooms
* `/sendreq.php` → Send room request
* `/ownerapp.php` → Manage applications

---

## ⚙️ Installation / Setup Guide

### 1. Clone the repository

git clone https://github.com/bibeko7/hostel_project-php.git

### 2. Move project to server folder

Place the project inside:

* XAMPP → `htdocs`
* WAMP → `www`

### 3. Setup database

* Open **phpMyAdmin**
* Create a new database (e.g., `hostel_db`)
* Import the `.sql` file (if available)

### 4. Configure database

Update database connection in your PHP config file:

* hostname: localhost
* username: root
* password: (empty by default)
* database name: hostel_db

### 5. Run the project

Open browser and go to:
http://localhost/hostel_project-php/

---

## 🔐 User Roles

* **Student** → Search and apply for rooms
* **Owner** → Add and manage rooms

---



## ⚠️ Important Notes

* Do not upload sensitive files like `.env`
* Make sure XAMPP/WAMP server is running
* Database must be properly connected

---

## 👨‍💻 Author

* Bibek (GitHub: https://github.com/bibeko7)

---

## 📄 License

This project is developed for educational purposes.
