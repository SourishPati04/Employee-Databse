# Employee-Databse ##

# Employee Database App (Java JDBC)

This is a simple **Java console-based application** that demonstrates **CRUD operations** on an Employee database using **JDBC**.  
It allows users to **Add, View, Update, and Delete employees** in a MySQL database.

---

## 🚀 Features
- Add a new employee (Name, Department, Salary)
- View all employees
- Update an employee’s salary
- Delete an employee
- Menu-driven console app

---

## 🛠️ Technologies Used
- **Java (JDBC)**
- **MySQL Database**
- **PreparedStatement & ResultSet**

---

## ⚙️ Setup Instructions

### 1. Database Setup
Run the following SQL commands in MySQL:

```sql
CREATE DATABASE employeeDB;

USE employeeDB;

CREATE TABLE employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(50),
    department VARCHAR(50),
    salary DOUBLE
);
