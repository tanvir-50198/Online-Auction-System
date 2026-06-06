# 🏷️ Online Auction System

### Full-Stack Web Application using PHP, MySQL, AJAX & MVC Architecture

A complete web-based auction platform that enables users to buy and sell products through competitive bidding. The system provides separate dashboards for Buyers, Sellers, and Administrators while offering real-time auction management, AJAX-powered interactions, and secure database operations.

---

## 📖 Project Overview

The Online Auction System is designed to provide a transparent and efficient online marketplace where sellers can list products for auction and buyers can compete through bidding. The platform automates auction management, winner selection, watchlists, reviews, and administrative monitoring.

This project was developed using:

* PHP (Procedural)
* MySQL Database
* HTML5 & CSS3
* JavaScript (AJAX)
* MVC Architecture

---

## ✨ Features

### 👤 Buyer Features

* User Registration & Login
* Browse Active Auctions
* AJAX Search & Filtering
* View Auction Details
* Real-Time Countdown Timer
* Place Bids Instantly via AJAX
* Watchlist Management
* Track Bid Status
* Profile Management
* Change Password
* Upload Profile Picture
* Review Sellers

---

### 🧑‍💼 Seller Features

* Seller Registration & Login
* Create Auction Listings
* Upload Product Images
* Edit Listings (Before Bids Exist)
* Delete Listings
* Monitor Live Bids
* AJAX-Based Bid Updates
* View Auction Results
* Review Winning Buyers

---

### 👑 Admin Features

* Admin Dashboard
* Manage Users
* Activate/Deactivate Accounts
* Delete Listings
* Category Management
* Create Admin Accounts
* Monitor Platform Statistics

---

## 🚀 Technologies Used

| Technology   | Purpose                   |
| ------------ | ------------------------- |
| PHP          | Backend Development       |
| MySQL        | Database Management       |
| HTML5        | Structure                 |
| CSS3         | Styling                   |
| JavaScript   | Client-side Functionality |
| AJAX         | Real-Time Updates         |
| XAMPP        | Local Server Environment  |
| Git & GitHub | Version Control           |

---

## 🏗️ System Architecture

The project follows the MVC (Model-View-Controller) architecture.

### Model

Handles database operations and queries.

### View

Responsible for user interface and presentation.

### Controller

Processes requests and controls application logic.

---

## 📂 Project Structure

```text
auction-system/
│
├── config/
│   └── database.php
│
├── models/
│
├── controllers/
│
├── views/
│   ├── buyer/
│   ├── seller/
│   ├── admin/
│   └── partials/
│
├── ajax/
│
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
├── uploads/
│   ├── profiles/
│   └── listings/
│
├── includes/
│
├── database.sql
│
├── index.php
├── logout.php
└── README.md
```

---

## 🗄️ Database Tables

### Users

Stores buyer, seller, and admin accounts.

### Categories

Stores auction categories.

### Listings

Stores auction information and product details.

### Bids

Stores bidding history and bid amounts.

### Watchlist

Stores saved auctions for buyers.

### Reviews

Stores ratings and feedback after auction completion.

---

## ⚙️ Installation Guide

### Requirements

* PHP 7.4+
* MySQL
* XAMPP
* Git (Optional)

### Setup Steps

#### 1. Clone Repository

```bash
git clone https://github.com/your-username/online-auction-system.git
```

#### 2. Move Project

Copy the project folder into:

```text
C:\xampp\htdocs\
```

#### 3. Start XAMPP

Start:

* Apache
* MySQL

#### 4. Create Database

Open:

```text
http://localhost/phpmyadmin
```

Create a database named:

```text
auction_db
```

Import:

```text
database.sql
```

#### 5. Configure Database

Update:

```php
define('DB_HOST', 'localhost');
define('DB_USER', 'root');
define('DB_PASS', '');
define('DB_NAME', 'auction_db');
```

#### 6. Create Upload Directories

```text
uploads/profiles/
uploads/listings/
```

#### 7. Run Application

Open:

```text
http://localhost/auction-system/
```

---

## 📡 AJAX Features

| Feature             | Description                          |
| ------------------- | ------------------------------------ |
| Search Auctions     | Dynamic search without page refresh  |
| Place Bid           | Instant bid submission               |
| Live Bid Updates    | Seller receives bid updates          |
| Category Management | Admin manages categories dynamically |

---

## 🔒 Security Features

* Session-Based Authentication
* Role-Based Authorization
* Password Hashing
* Input Validation
* SQL Injection Prevention
* Prepared Statements
* Secure File Upload Handling
---

## 🔮 Future Improvements

* Email Notifications
* Payment Gateway Integration
* Real-Time WebSocket Bidding
* Mobile Responsive Design
* Password Recovery System
* Advanced Analytics Dashboard
* Multi-Language Support

---

## 🎓 Academic Information

This project was developed as part of a university Web Technologies course to demonstrate full-stack web development concepts, database integration, AJAX communication, and MVC architecture.

---

## 👨‍💻 Author

### Tanvir Rahman

Computer Science & Engineering Student

#### Contributions

* System Design
* Database Design
* Buyer Module Development
* Seller Module Development
* AJAX Implementation
* Admin Dashboard Development
* Testing & Documentation

GitHub: https://github.com/tanvir-50198

---

## 📄 License

This project is developed for educational and academic purposes.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

**Thank You for Visiting This Repository!**
