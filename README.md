# -Supermarket_Management_System
Supermarket Management System is a desktop-based Java application built with Swing for GUI and MySQL as the backend. It helps supermarkets manage products, employees, and categories efficiently. The system features secure login, inventory tracking, employee management, and category organization.

# 🛒 Supermarket Management System

## 📌 Overview
The **Supermarket Management System** is a desktop-based application built in **Java (Swing)** with **MySQL** as the backend database. It is designed to help supermarkets efficiently manage **products, employees, and categories** through an intuitive graphical user interface (GUI). The system ensures smooth operations by enabling easy **addition, updating, and deletion** of records via **JDBC (Java Database Connectivity)**.

## 🚀 Features
### 🔐 Login System
- Secure authentication for registered employees  

### 👥 Employee Management
- Add new employees  
- Update employee passwords  
- Delete employee records  

### 📦 Product Management
- Add new products  
- Update product quantities  
- Delete products  

### 🏷️ Category Management
- Add new product categories  
- Delete categories  

### 🗄️ MySQL Database Integration
- Stores and retrieves data using **JDBC** for data persistence  

## 🏗️ Technologies Used
- **Java (JDK 8+)** – Core programming language  
- **Java Swing** – For creating the graphical user interface  
- **MySQL** – Database for storing supermarket data  
- **JDBC (Java Database Connectivity)** – For seamless database interaction  
- **NetBeans IDE (version 22)** – Development environment  

## 📊 Database Structure
### 🛠️ `employees` Table
| Column Name  | Data Type   | Description           |
|-------------|------------|----------------------|
| EID         | INT (PK)   | Employee ID         |
| EmployeeName | VARCHAR   | Name of Employee    |
| Password    | VARCHAR   | Secure password     |

### 📦 `products` Table
| Column Name  | Data Type   | Description       |
|-------------|------------|------------------|
| PID         | INT (PK)   | Product ID       |
| ProductName | VARCHAR   | Name of Product  |
| Quantity    | INT       | Stock Available  |

### 🏷️ `categories` Table
| Column Name  | Data Type   | Description            |
|-------------|------------|-----------------------|
| CID         | INT (PK)   | Category ID          |
| Category    | VARCHAR   | Product Category Name |
.
- Install **JDK 8+**  
- Install **MySQL Server**  
- Install **NetBeans IDE (or any Java IDE of your choice)**  


