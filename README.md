# WebsiteEmployeeLeaveamanagement-full-stack
Overview
This is a full-stack web application for managing employee leave requests. The application allows employees to request leaves, and managers can approve or reject these requests. It is built using PHP for the backend, HTML/CSS/JavaScript for the frontend, and MySQL for the database.

Features
User Authentication:

Secure login for employees and administrators.
Password encryption using hashing.
Employee Dashboard:

View personal leave balance.
Submit new leave requests.
Track the status of leave requests (approved/rejected/pending).
Admin Dashboard:

Manage employee accounts.
View all leave requests.
Approve or reject leave requests.
Generate leave reports.
Leave Management:

Different types of leaves (sick leave, casual leave, etc.).
Leave balance tracking.
Notifications for leave request status updates.
Technology Stack
Frontend:
HTML5, CSS3, JavaScript, Bootstrap
Backend:
PHP
Database:
MySQL
Server:
Apache (XAMPP/LAMP/WAMP)
Installation
Prerequisites
PHP 7.x or later
MySQL 5.x or later
Apache server (XAMPP, LAMP, WAMP, or any other server)
Web browser (Chrome, Firefox, etc.)
Steps
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/WebsiteEmployeeLeaveManagement.git
Move the project to your server's root directory:

For XAMPP: Move the folder to C:/xampp/htdocs/
For WAMP: Move the folder to C:/wamp64/www/
For LAMP: Move the folder to /var/www/html/
Import the Database:

Open your browser and go to http://localhost/phpmyadmin.
Create a new database (e.g., employee_leave_management).
Import the employee_leave_management.sql file located in the database/ directory.
Update Database Configuration:

Go to the project folder and open config.php.
Update the following lines with your database credentials:
php
Copy code
define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'your_username');
define('DB_PASSWORD', 'your_password');
define('DB_DATABASE', 'employee_leave_management');
Run the Application:

Open your browser and navigate to http://localhost/WebsiteEmployeeLeaveManagement.
You should see the login page of the application.
