# 📚 School Management System (SMS)

## 📌 Project Overview

The **School Management System (SMS)** is a console-based application developed using **Python and MySQL Connectivity**.
It helps manage school staff records, login authentication, salary management, and department-based operations efficiently.

This project demonstrates CRUD operations using Python with MySQL database integration.

---

## 🚀 Features

### 🔐 1. User Authentication

* Login system
* Register new users
* Delete existing usernames
* Password validation

### 👨‍🏫 2. Staff Management

* Insert employee records
* Update employee details
* Delete employee records
* Display records

### 💰 3. Salary Management

* View salary details
* Increment salary (individual / department wise)

### 🏢 4. Department Operations

* View staff by department
* Count employees department-wise

---

## 🛠️ Technologies Used

* **Python**
* **MySQL**
* **mysql-connector-python**
* Console-based UI

---

## 🗄️ Database Structure

### 1️⃣ Login Table

| Column Name | Data Type |
| ----------- | --------- |
| Username    | VARCHAR   |
| Password    | INT       |

### 2️⃣ Personal_Details Table

| Column Name | Data Type |
| ----------- | --------- |
| Emp_Code    | VARCHAR   |
| Emp_Name    | VARCHAR   |
| DOB         | DATE      |
| ACC_No      | VARCHAR   |
| Phone_No    | BIGINT    |
| Gender      | VARCHAR   |
| Age         | INT       |

### 3️⃣ Staff_Detail Table

| Column Name   | Data Type |
| ------------- | --------- |
| Emp_Code      | VARCHAR   |
| DOJ           | DATE      |
| DEPT          | VARCHAR   |
| Salary        | FLOAT     |
| Experience    | INT       |
| Qualification | VARCHAR   |
| Designation   | VARCHAR   |

---

## ⚙️ Installation Guide

### Step 1: Install MySQL

Make sure MySQL Server is installed and running.

### Step 2: Install Python Library

```bash
pip install mysql-connector-python
```

### Step 3: Create Database

```sql
CREATE DATABASE sms;
USE sms;
```

Create required tables manually in MySQL.

### Step 4: Run the Program

```bash
python SMS.py
```

---

## 📋 Program Flow

1. Start Application
2. Login or Register
3. Choose Operation:

   * Display
   * Insert
   * Update
   * Delete
   * Salary Operations
4. Perform selected operation
5. Continue or Exit

---

## 🔒 Security Note

* Password is stored as integer (4-digit)
* Uses basic dictionary-based authentication
* Not encrypted (Educational purpose only)

---

## 🎯 Learning Outcomes

* Python-MySQL Connectivity
* CRUD operations
* SQL Queries
* Authentication System
* Console Menu Design
* Database Management

---

## 👨‍💻 Developed By

**Gnaneshwar R L**
+91 8608698986
gnaneshwarnani8605@gmail.com
12th Grade Project
School Management System
Academic Year: 2022-2023
