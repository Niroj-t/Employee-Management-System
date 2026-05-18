# Employee Management System

## 📌 Project Overview

The **Employee Management System** is a desktop-based application designed to efficiently manage employee data within an organization. This project allows users to store, retrieve, update, and delete employee information using a structured database system.

The main goal of this system is to reduce manual work and improve accuracy in managing employee information. It helps administrators keep track of employee details such as personal information, job roles, and other relevant data in an organized way.

---

## 🚀 Features

* ➕ Add new employee details
* 🔍 Search employee by ID or name
* 📄 View all employee records in a table format
* ✏️ Update existing employee information
* ❌ Delete employee records when they leave the company
* 🖨️ Print employee details

---

## 🛠️ Tech Stack

* **Frontend:** Java Swing (GUI)
* **Backend:** Java
* **Database:** MySQL
* **IDE:** IntelliJ IDEA / Eclipse

---

## 📂 Project Structure

```
Employee-Management-System/
│── src/
│   ├── employee/management/system/
│   │   ├── AddEmployee.java
│   │   ├── ViewEmployee.java
│   │   ├── UpdateEmployee.java
│   │   ├── RemoveEmployee.java
│   │   └── Conn.java
│── icons
│── README.md
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/employee-management-system.git
   ```

2. Open the project in your preferred IDE.

3. Set up the MySQL database:

   * Create a database (e.g., `employee_db`)
   * Import the provided SQL file

4. Configure database connection in `Conn.java`:

   ```java
   Connection c = DriverManager.getConnection("jdbc:mysql://localhost:3306/employee_db", "username", "password");
   ```

5. Run the main class to start the application.

---

## 📸 Screenshots

https://github.com/Niroj-t/Employee-Management-System/blob/da86e5be2c1940c8f3ecc3d817b48308a0f044f5/Screenshot%202026-05-18%20141835.png

https://github.com/Niroj-t/Employee-Management-System/blob/da86e5be2c1940c8f3ecc3d817b48308a0f044f5/Screenshot%202026-05-18%20141942.png

https://github.com/Niroj-t/Employee-Management-System/blob/da86e5be2c1940c8f3ecc3d817b48308a0f044f5/Screenshot%202026-05-18%20141956.png

https://github.com/Niroj-t/Employee-Management-System/blob/da86e5be2c1940c8f3ecc3d817b48308a0f044f5/Screenshot%202026-05-18%20142007.png

https://github.com/Niroj-t/Employee-Management-System/blob/da86e5be2c1940c8f3ecc3d817b48308a0f044f5/Screenshot%202026-05-18%20142022.png


---

## 🎯 Use Cases

* Manage employee records in offices or organizations
* Useful for HR departments
* Academic project for learning Java GUI and database integration

---

