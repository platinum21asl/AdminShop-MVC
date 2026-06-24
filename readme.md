# 🛒 AdminShop-MVC

A dynamic and responsive e-commerce platform built using the **CodeIgniter** framework and the **SB Admin 2** interface. This project implements a structured *Model-View-Controller* (MVC) architecture, designed to provide a seamless shopping experience for customers and effortless store management for administrators.

## ✨ Key Features

### 🛍️ Customer Side (User)
*   **Product & Category Catalog:** Structured product navigation based on categories (e.g., Electronics, Men's Clothing).
*   **Shopping Cart System:** Intuitive addition, removal, and management of shopping items prior to checkout.
*   **Checkout & Payment:** Secure and structured order completion process.
*   **User Authentication:** Registration and login system for a personalized shopping history.

### ⚙️ Administrator Side (Admin Panel)
*   **Analytics Dashboard:** Overview of sales data and store performance with graphical visualization (integrated with Chart.js).
*   **Inventory Management:** Real-time *Create, Read, Update, Delete* (CRUD) operations for product data.
*   **Transaction Management:** Review incoming orders, print capabilities, and detailed *Invoice* history.
*   **DataTables Integration:** Fast search, sorting, and pagination features for managing large amounts of data.

## 🛠️ Tech Stack

*   **Backend:** PHP, CodeIgniter 3
*   **Frontend:** HTML5, CSS3, SCSS, JavaScript
*   **UI Framework:** Bootstrap 4 (SB Admin 2 Template)
*   **Database:** MySQL
*   **Libraries/Plugins:** FontAwesome (Icons), Chart.js (Charts), DataTables (Table Management)

## 🚀 Installation Guide (Local Development)

Follow these steps to run the project in your local environment:

1.  **System Requirements:** Ensure you have installed a local web server (such as XAMPP, Laragon, or MAMP) that supports PHP and MySQL.
2.  **Clone Repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
3.  **Move the Folder:** Place the project folder inside your web server's document root directory (e.g., `htdocs` for XAMPP or `www` for Laragon).
4.  **Database Configuration:**
    *   Open phpMyAdmin or any other database client.
    *   Create a new database (e.g., `db_toko_online`).
    *   Import the provided SQL database file into the newly created database.
5.  **Application Configuration:**
    *   Open the `application/config/database.php` file.
    *   Adjust the database configuration:
        ```php
        'hostname' => 'localhost',
        'username' => 'root', // adjust to your database username
        'password' => '',     // adjust to your database password
        'database' => 'db_toko_online',
        ```
    *   Adjust the `$config['base_url']` value inside `application/config/config.php` to match your local URL.
6.  **Run the Application:** Open a web browser and access your project's local URL (e.g., `http://localhost/toko_online`).

## 👨‍💻 Author

*   **Daniel Renato** - *Software Engineer*
