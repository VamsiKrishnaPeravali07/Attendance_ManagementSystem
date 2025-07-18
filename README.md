
## 📘 Attendance Management System (MySQL)

A lightweight and efficient **Attendance Management System** developed using **MySQL**, designed to manage and track attendance records for students or employees. Ideal for educational institutions and small organizations seeking a digital alternative to manual attendance tracking.

---

### 🚀 Features

* ✅ Mark and update daily attendance
* 👨‍🏫 Admin panel to manage students/employees
* 📅 View and filter attendance by date, user, or class
* 📊 Attendance summary and percentage calculation
* 🧾 Generate printable reports (PDF/CSV)
* 🔐 Secure login for admin and staff
* 📁 Database-driven with easy setup and clean UI

---

### 🛠️ Technologies Used

* **Frontend**: HTML, CSS, JavaScript, Bootstrap
* **Backend**: PHP
* **Database**: MySQL
* **Authentication**: PHP session-based login

---

### ⚙️ Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/attendance-management-php.git
   ```

2. **Import the database**

   * Open **phpMyAdmin**
   * Create a new database (e.g., `attendance_db`)
   * Import the provided `attendance_db.sql` file from the project

3. **Configure the database connection**

   * Open `config.php` or `db.php`
   * Update DB credentials:

     ```php
     $host = "localhost";
     $user = "root";
     $password = "";
     $database = "attendance_db";
     ```

4. **Run the project**

   * Move the project folder to your local server directory (e.g., `htdocs` for XAMPP)
   * Open your browser:

     ```
     http://localhost/attendance-management-php/
     ```

---

### 📸 Screenshots

> *(Optional: Add UI screenshots for login, dashboard, attendance table, etc.)*

---

### 🔐 Default Login (for testing)
**ADMIN LOGIN**
URL: http://localhost/employee-attendance-management/admin/
Emailid: admin
Password: AdminEAM@123#$



**EMPLOYEE LOGIN**
URL: http://localhost/employee-attendance-management/
Emailid: jane
Password: 123

*(You can change this in the database later.)*

---

### 📄 License

This project is open-source under the **MIT License**.
Feel free to fork and enhance it for your institution or team.
