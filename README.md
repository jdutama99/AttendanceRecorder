# AttendanceRecorder
This application allows user to record their attendance

Simple Attendance Recorder

Explanation:
For project, I decided to create an attendance recorder. This project is designed with JavaScript language utilizing HTML and CSS platform. This Attendance Management System has two sides: an admin side and a user side that allows users to enter attendance information. The admin has a significant role to play in overseeing this process. The user is responsible for all core tasks on the admin side of this initiative.

Required hardware and environment specifications
•	Windows machine 
•	Google Chrome

How to Run this Attendance Management System in JavaScript
Requirements:
•	Download and Install XAMPP. 
Setup/Installation
•	Open your XAMPP Control Panel and start “Apache” and “MySQL”.
•	Extract the source code zip file.
•	If you are using XAMPP, copy the extracted source code folder and paste it into the XAMPP’s “htdocs” directory.
•	Open a web browser and browse the PHPMyAdmin. http://localhost/phpmyadmin
•	Create a new database naming “attendance”.
•	Import the SQL file provided. The file is known as “attendance.sql” and located inside the “database file” folder.
•	Browse the Web Application in a browser/chrome. i.e. http://localhost/attendance

Features of Attendance Management System 
•	Homepage ( localhost/attendance/admin/home.php) – From this page user can access other pages such as admin, students, and the records page.
•	Manage User Account (localhost/attendance/admin/admin.php)– The user accounts will be handled by the administrator. Users can be added, modified, and removed in the system by the administrator.
•	Student Management(localhost/attendance/admin/student.php) – The student account will be managed by the administrator. Admins have the ability to integrate, upgrade, and uninstall students from the system.
•	Manage Student Record (localhost/attendance/admin/record.php) – The student record will be controlled by the administrator. The time and date of the student's login are visible to the administrator.
•	Login and Logout(localhost/attendance/admin/index.php) – By default one of the security features of this system is the secure login and logout system. The login and logout system of this Attendance Management System in JavaScript source code uses a session. It means that the user can only log in at once on the same browser. To log in please use this credential.
o	Username: admin
o	Password :admin
•	Log attendance (localhost/attendance/index.php)  – User can input his/her id to have their attendance recorded. The data from this action can be viewed in the student record page.
