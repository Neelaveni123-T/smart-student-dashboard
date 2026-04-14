# 🎓 Smart Student Dashboard System

A full-stack web application built using **Flask, MongoDB, HTML, CSS, and JavaScript** to manage student attendance and provide analytics through an interactive dashboard.

---

## 🚀 Features

### 🔐 Authentication

* User Signup & Login
* Password hashing using bcrypt
* Role-based access (Student / Admin)

### 👨‍🎓 Student Dashboard

* Add daily attendance (Present / Absent)
* View personal attendance records
* Filter attendance by status
* Total records display
* Date validation (prevents future entries)

### 👨‍💼 Admin Dashboard

* View all student attendance data
* Search by email
* Filter by attendance status
* View total number of unique students
* Attendance percentage calculation
* Interactive pie chart visualization (Chart.js)

### ⚡ Additional Features

* Duplicate attendance prevention
* Logout functionality
* Role-based page access protection
* Responsive UI with modern design

---

## 🛠️ Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Flask (Python)
* **Database:** MongoDB
* **Visualization:** Chart.js

---

## 📁 Project Structure

```
Smart Student Dashboard/
│
├── backend/
│   ├── app.py
│   └── config.py
│
├── frontend/
│   ├── login.html
│   ├── signup.html
│   ├── dashboard.html
│   ├── admin.html
│   ├── script.js
│   └── style.css
│
└── README.md
```

---

## ⚙️ Local Setup

### 1️⃣ Install Dependencies

```bash
pip install flask pymongo bcrypt flask-cors
```

### 2️⃣ Start MongoDB

```bash
mongod
```

### 3️⃣ Run the Application

```bash
python app.py
```

### 4️⃣ Open in Browser

```
http://127.0.0.1:5000
```

---

## 🔑 Default Roles

* **Student:** Created via signup
* **Admin:** Manually set in MongoDB

Example:

```json
"role": "admin"
```

---

## 📊 Key Functionalities

* Attendance tracking system
* Role-based dashboard redirection
* Search and filter functionality
* Real-time analytics using charts
* Secure authentication system

---

## 🎯 Evaluation Highlights

* Clean UI/UX design
* Full-stack implementation
* Database integration with MongoDB
* Role-based access control
* Interactive dashboard analytics

---

## 🎤 Project Description

This project simulates a real-world student management system where students can track their attendance and administrators can monitor and analyze attendance data through dashboards and visualizations.


