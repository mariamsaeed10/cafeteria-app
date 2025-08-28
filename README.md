# 🍽️ Cafeteria Web Application

## 📌 Overview
The **Cafeteria Web Application** is a simple web-based system built using the **Flask Framework** and **SQLite database**.  
It allows customers to register, log in, browse products, place orders, and for the admin to manage the menu and order statuses.  

---

## 🗂️ Project Contents
After extracting the ZIP file, you will find:  

- **app.py** → Main Flask application (ready to run).  
- **requirements.txt** → Dependencies list.  
- **cafeteria.db** → Pre-configured SQLite database with demo data.  
- **templates/** → HTML pages (register, login, menu, cart, dashboard, admin pages).  
- **static/style.css** → Styling (pink theme + hover effects).  
- **static/images/** → Product images.  

---

## 🔑 Login Credentials
- **Admin account**:  
  - Username: `admin`  
  - Password: `admin`  

- **Demo User account**:  
  - Username: `mariam`  
  - Password: `mariam123`  

---

## 🍔 Preloaded Products
- Pizza  
- Burger  
- Orange Juice  
- Coffee  

(With product images inside `static/images/`)  

---

## 🏗️ Tech Stack
- **Frontend:** HTML, CSS  
- **Backend:** Flask (Python)  
- **Database:** SQLite  

---

## 📦 Dependencies
Make sure to install the following:
```txt
Flask
Flask_SQLAlchemy
Flask_Login
