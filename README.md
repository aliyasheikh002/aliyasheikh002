# Student Scheduling System

## Project Overview
The **Student Scheduling System** is a web-based application developed using **JSP (Java Server Pages)** for the frontend and **SQL Workbench (MySQL)** for the backend. This system is designed to help colleges manage student schedules, exam timetables, attendance, lecture timings, and notices efficiently. It features role-based access, allowing **admins** to manage data while **students** can only view it.

## Features
1. **Student Login**  
   - Secure login system for students.
2. **Admin Panel**  
   - Admin can manage data (add/delete/update) for schedules, attendance, notices, and lecture timings.
3. **Exam Timetable Management**  
   - Displays exam schedules with backend integration.
4. **Student Attendance Tracking**  
   - Admin updates student attendance records.
5. **College Notices**  
   - Admin posts important notices for students.
6. **Lecture Timings**  
   - Subject-wise lecture schedules.
7. **Reports & Analytics**  
   - Displays reports using bar charts.
8. **Role-Based Access**  
   - **Admin:** Can update all data.
   - **Student:** Can only view data.
9. **Attractive UI & Full Animation**  
   - Professional and engaging design with header, footer, and menu on every page.

## Technologies Used
- **Frontend:** JSP, HTML, CSS, JavaScript
- **Backend:** MySQL (SQL Workbench)
- **Server:** Apache Tomcat
- **Database Connection:** JDBC

## Installation Guide
### Prerequisites
- Java Development Kit (JDK)
- Apache Tomcat Server
- MySQL Workbench
- Eclipse IDE (or any other JSP-supported IDE)

### Setup Instructions
1. **Database Setup:**
   - Open MySQL Workbench.
   - Create a new database: `student_schedule_db`.
   - Import the provided SQL file (`student_schedule.sql`).
2. **Project Deployment:**
   - Copy the project folder into your Eclipse workspace.
   - Open Eclipse and import the project.
   - Configure Apache Tomcat Server.
   - Update `DBConnection.java` with your MySQL username and password.
3. **Run the Project:**
   - Start Apache Tomcat.
   - Open a browser and go to `http://localhost:8080/StudentSchedulingSystem/`.

## Usage
1. **Login as Admin:**
   - Default Admin Credentials:
     - Username: `admin`
     - Password: `admin123`
   - Manage schedules, attendance, notices, and more.
2. **Login as Student:**
   - View exam schedules, attendance, and college notices.

## Database Structure
- **Users:** Stores admin and student login credentials.
- **Exam_Timetable:** Stores exam schedules.
- **Attendance:** Stores student attendance records.
- **Notices:** Stores college notices.
- **Lecture_Timings:** Stores subject-wise lecture timings.

## Future Enhancements
- Implement real-time notifications.
- Add student profile management.
- Improve UI with modern frameworks.

## Author
Developed by: **[Your Name]**

For any queries, contact: **[Your Email]**


aliyasheikh002/aliyasheikh002 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
