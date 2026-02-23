# Hostel Management and Booking System (HMBS)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📝 Overview
The **Hostel Management and Booking System (HMBS)** is a comprehensive web-based solution designed to digitize the administrative workflows of student residences. It replaces manual paper-based record-keeping with a secure, relational database system to manage student registrations, room allocations, and financial tracking.

This project was developed using a **Waterfall Methodology** to ensure rigorous requirement analysis and systematic testing (UAT).

## 📌 Table of Contents
* [Key Features](#key-features)
* [Technical Stack](#technical-stack)
* [System Architecture](#system-architecture)
* [Database Schema](#database-schema)
* [Installation & Setup](#installation--setup)
* [Methodology](#methodology)
* [Roadmap](#roadmap)
* [License](#license)
* [Contact](#contact)

## ✨ Key Features
* **Student Portal:** Registration, profile management, and real-time room availability checking.
* **Automated Booking:** Streamlined room allocation logic to prevent overbooking.
* **Admin Dashboard:** Centralized control for managing student records, room status, and payment logs.
* **Financial Tracking:** Automated reporting for occupancy rates and revenue collection.
* **Responsive Design:** Built with Bootstrap to ensure accessibility across desktop and mobile devices.

## 🛠 Technical Stack
| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Frontend** | HTML5, CSS3, JavaScript | User interface and client-side interaction. |
| **Styling** | Bootstrap 5 | Responsive grid system and UI components. |
| **Backend** | PHP 8.x | Server-side logic and API handling. |
| **Database** | MySQL | Relational data storage and management. |
| **Environment** | XAMPP / Apache | Local development and server hosting. |

## 🏗 System Architecture
The system follows a classic **Client-Server Architecture**. The frontend interacts with the PHP backend via HTTP requests, which in turn performs CRUD (Create, Read, Update, Delete) operations on the MySQL database.



## 📊 Database Schema
The relational structure is optimized for data integrity. Key tables include:
* `users` - Authentication and role-based access data.
* `students` - Personal details and academic information.
* `rooms` - Capacity, status (Available/Full), and pricing.
* `bookings` - Mapping students to specific rooms with stay durations.
* `payments` - Transaction history and balance tracking.



## 🚀 Installation & Setup

### Prerequisites
* **XAMPP** (or any WAMP/LAMP stack).
* **PHP 7.4+** and **MySQL**.

### Steps
1. **Clone the Repository**
   ```bash
   git clone [https://github.com/your-username/HMBS.git](https://github.com/your-username/HMBS.git)
   cd HMBS

```

2. **Database Import**
* Open PHPMyAdmin and create a database named `hostel_db`.
* Import the `database/hostel.sql` file provided in the repository.


3. **Configuration**
* Open `includes/config.php` and update your database credentials:


```php
$db_host = 'localhost';
$db_user = 'root';
$db_pass = '';
$db_name = 'hostel_db';

```


4. **Deploy**
* Move the project folder to your `htdocs` directory.
* Navigate to `http://localhost/HMBS` in your browser.



## 📈 Methodology

This project utilized the **Waterfall Model**, ensuring each phase was completed and verified before proceeding:

1. **Requirements:** Defining functional and non-functional needs.
2. **Design:** Creating ERDs, DFDs, and wireframes.
3. **Implementation:** Coding the PHP backend and Bootstrap frontend.
4. **Testing:** Unit testing and User Acceptance Testing (UAT).

## 🗺 Roadmap

Future contributions are encouraged in the following areas:

* [ ] **Security:** Implementing password hashing (`password_hash()`) to replace legacy MD5.
* [ ] **Notifications:** Email/SMS alerts for booking confirmations.
* [ ] **Analytics:** A visual chart dashboard for admin occupancy reports.
* [ ] **File Export:** PDF generation for student payment receipts.

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for more information.

## ✉️ Contact & Contributors
Project Owner: [Repository Maintainer]

Contributor: shillat (github username) — Documentation & Technical Refactoring

Project Link: https://github.com/bos-com/HMBS

```



