# Hospital Management System

![hospital_management_system](https://github.com/RedisMadani/hospital-management-app/assets/136177376/2658b47d-7248-4925-a559-b723b92775f5)

## Introduction

The Hospital Management System is a web application developed using MySQL, PHP, and Bootstrap. It provides an efficient platform for managing hospital operations, including patient appointments, doctor schedules, and administrative tasks. The system aims to streamline hospital processes and enhance the overall healthcare experience.

## Key Features

The system is designed to address specific needs and challenges in hospital management. Some of the notable features include:

1. **Appointment Approval**: Doctors can accept appointment requests, notifying patients of their approved appointments.

2. **Email ID Validation**: Users are prevented from registering with duplicate email addresses to ensure data integrity.

3. **Password Encryption**: Passwords are securely encrypted, and the password field is hidden in the admin panel for enhanced security.

4. **Pagination**: Implemented pagination across all list views for efficient data navigation.

5. **Bug Fix**: Resolved a bug where bill payment receipts contained multiple records when a patient had multiple appointments with the same doctor.

6. **Enhanced Prescription Statement**: Added more fields to the prescription statement for specificity.

7. **Detailed Payment Records**: Included payment details such as payment date and amount in the system.

8. **Export Functionality**: Implemented an export button in the admin module to export all details to an Excel sheet for easy data management.

## Prerequisites

Before running the project, ensure you have the following prerequisites in place:

- **XAMPP Web Server**: Install XAMPP on your machine to set up the web server.
- **Text Editor**: Use any code editor, preferably VS Code or Sublime Text, for code editing.
- **Web Browser**: Make sure you have an up-to-date web browser for testing.

## Technologies Used

The project leverages various technologies and languages, including:

- **HTML5/CSS3**: For creating the web interface.
- **JavaScript**: Used for dynamic content updates.
- **Bootstrap**: A CSS framework for responsive design.
- **XAMPP**: A web server powered by Apache Friends.
- **PHP**: For server-side scripting.
- **MySQL**: A relational database management system.
- **TCPDF**: Used to generate PDF documents.

## Installation Steps

To run the project on your local machine, follow these steps:

1. Download and install XAMPP on your machine.

2. Clone or download the project repository.

3. Extract all project files and move them to the 'htdocs' folder within your XAMPP directory.

4. Start the Apache and MySQL services from the XAMPP control panel.

5. Open your web browser and navigate to 'localhost/phpmyadmin'.

6. In phpMyAdmin, create a new database named 'myhmsdb'.

7. Import the 'myhmsdb.sql' file into your newly created database.

8. Open a new browser tab and enter 'localhost/foldername' in the URL to access the project.

9. You're all set! The project should now be running on your local machine.

## Software Used

- **XAMPP**: Installed on an Ubuntu 19.04 machine with Apache2 Server and MySQL.
- **Sublime Text 3.2**: Used as a text editor.
- **Google Chrome**: Version 77.0.3865.90 was used to run the project locally.

## Starting Apache and MySQL in XAMPP

The XAMPP Control Panel provides a user-friendly interface to manually start and stop Apache and MySQL. To start these services manually, follow these steps:

1. Launch the XAMPP Control Panel.

2. Click the 'Start' button under 'Actions' for Apache and MySQL.

## Getting Started with the Project

The Hospital Management System consists of three main modules accessible from the homepage:

### 1. Patient Module

- Allows patients to create accounts, book appointments with doctors, and view their appointment history.
- Registration requires users to provide first name, last name, email, contact number, password, and select their gender.
- After registration, patients are redirected to their dashboard where they can book appointments and view appointment history.

### 2. Doctor Module

- Doctors can log in to their accounts to view their appointment schedules.
- Registration for doctors is managed by the admin.
- The dashboard displays the doctor's appointments and includes a search feature for efficient appointment management.

### 3. Admin Module

- The admin module provides comprehensive control over the system.
- Admins can view lists of patients, doctors, and appointments, search for specific records, and add new doctors.
- Additionally, the admin can access and review user feedback and queries received through the 'Contact' page.

## Updates

### 1. Cancel Appointments

- Both patients and doctors can delete their appointments.
- Canceled appointments are marked with a "deleted by you" label in the "Current Status" column.

### 2. Remove Doctors by Admin

- Admins have the authority to remove doctors from the system for better management.

This Hospital Management System aims to enhance hospital operations and provide efficient healthcare services. It includes features for patients, doctors, and administrators, ensuring a smooth healthcare management process.
