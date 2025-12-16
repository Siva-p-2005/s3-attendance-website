PROJECT TITLE
-------------
Hosting a Static Website for Attendance Calculation using AWS S3


ABSTRACT
--------
This project focuses on designing and hosting a static website for student
attendance calculation using Amazon Web Services (AWS) S3. The system allows
students to submit attendance requests, which are reviewed and approved by
an administrator. Once approved, attendance records are updated and displayed.

Using AWS S3 for static website hosting provides a low-cost, scalable, and
highly available solution without the need for server maintenance. This
project demonstrates cloud-based deployment and basic attendance management.


OBJECTIVES
----------
1. To create a static website for student attendance submission.
2. To host the website using Amazon S3.
3. To allow administrators to approve attendance requests.
4. To display approved attendance records.
5. To demonstrate cloud-based static website hosting.


TOOLS AND TECHNOLOGIES
---------------------
- AWS S3 : Static website hosting
- HTML : Web structure
- CSS : Styling and layout
- JavaScript : Client-side logic
- AWS IAM : Permission management
- JSON / Local Storage : Attendance data storage
- Web Browser : Accessing the application


PROJECT DESCRIPTION
-------------------
The Attendance Management System is a web-based application designed for
educational institutions. Students submit attendance requests through the
website. These requests are sent to an admin panel where the administrator
can approve or reject them.

After approval, attendance is marked and displayed to the student. The
entire website is hosted on AWS S3, eliminating the need for servers and
reducing cost while improving availability.


SYSTEM ARCHITECTURE
-------------------
- Frontend : HTML, CSS, JavaScript
- Hosting Platform : AWS S3 Static Website Hosting
- Data Handling : JSON / Browser Local Storage
- Security : AWS IAM access control


FLOW OF OPERATION
-----------------
Student submits attendance request
        |
        v
Admin reviews request
        |
        v
Admin approves or rejects request
        |
        v
Attendance record updated
        |
        v
Result displayed to student


ADVANTAGES
----------
- Low-cost hosting
- No server maintenance required
- Easy deployment
- Scalable and reliable
- Globally accessible
- Simple user interface


OUTPUT
------
- AWS S3 bucket created for static website hosting
- index.html uploaded successfully
- Website accessible using S3 URL
- Login page for Admin and Student
- Admin panel to approve requests
- Student panel showing approval status


CONCLUSION
----------
This project successfully demonstrates how AWS S3 can be used to host a
static website for attendance management. It provides a simple, cost-
effective, and scalable solution suitable for educational use cases and
cloud learning projects.
