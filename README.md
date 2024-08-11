# Expense and Budget Tracker - PHP Project

## Overview

The Expense and Budget Tracker is a PHP-based web application designed to help users manage their expenses and budget effectively. This project allows users to track their financial activities, including income and expenses, and generate reports to manage their budget efficiently.

## Features

- User Authentication (default admin credentials)
- Expense Tracking
- Income Tracking
- Budget Management
- Report Generation
- User Management

## Default Credentials

- **Username:** admin
- **Password:** admin123

## Installation Guide

### Prerequisites

1. **XAMPP/WAMP:** Ensure you have XAMPP or WAMP installed on your system.
2. **PHP:** The project requires PHP to be installed and configured on your system.
3. **MySQL:** MySQL is required for database management.

### Step-by-Step Installation

1. **Start the Server:**
   - Open your XAMPP/WAMP Control Panel.
   - Start the **Apache** and **MySQL** services.

2. **Download and Extract:**
   - Download the source code zip file for the Expense and Budget Tracker.
   - Extract the downloaded zip file.

3. **Copy the Source Code:**
   - If you are using **XAMPP**:
     - Copy the extracted source code folder.
     - Paste it into the XAMPP's `htdocs` directory (`C:\xampp\htdocs`).

   - If you are using **WAMP**:
     - Copy the extracted source code folder.
     - Paste it into the WAMP's `www` directory (`C:\wamp\www`).

4. **Database Setup:**
   - Open your browser and navigate to **PHPMyAdmin** by visiting: `http://localhost/phpmyadmin`.
   - Create a new database named `expense_budget_db`.
   - Import the provided SQL file:
     - The SQL file is named `expense_budget_db.sql` and is located inside the `database` folder of the extracted source code.
     - In PHPMyAdmin, select the `expense_budget_db` database.
     - Click on the `Import` tab and import the `expense_budget_db.sql` file.

5. **Run the Application:**
   - Open your browser and visit: `http://localhost/expense_budget`.
   - Log in using the default credentials provided above.

## Troubleshooting

- **Unable to Start Apache/MySQL:**
  - Ensure that no other applications are using port 80 (for Apache) or 3306 (for MySQL). If ports are in use, configure XAMPP/WAMP to use different ports.
  
- **Database Import Issues:**
  - Ensure that the `expense_budget_db` database is correctly created and selected before importing the SQL file.

- **Login Problems:**
  - Double-check that you are using the correct default credentials (Username: `admin`, Password: `admin123`).

## License

This project is open-source and free to use under the MIT License.

## Support

If you encounter any issues, feel free to raise them in the project repository or contact to me sohamkarmakar72@gmail.com

---

Enjoy tracking your expenses and managing your budget efficiently!

Developed by SkdevilS with Love
