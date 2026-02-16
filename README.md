# The Fabric Studio - Online Tailoring Platform

The Fabric Studio is a web-based application designed to bridge the gap between customers and professional tailors. Developed as a solution for door-to-door tailoring services in India, the platform allows users to find expert tailors in their city, view their portfolios, and book appointments from the comfort of their home.

## 🚀 Features

* **Multi-User Authentication**: Separate login and registration systems for Customers, Tailors, and Administrators.
* **Location-Based Search**: Users can explore professional tailors in major cities like Delhi, Mumbai, Jaipur, and Hyderabad.
* **Appointment Booking**: A dynamic booking form that captures user details and preferred meeting times using `datetime-local` integration.
* **Tailor Portfolios**: Displays tailor expertise, years of experience, and number of workers to help customers make informed decisions.
* **Responsive UI**: Parallax scrolling effects and interactive slideshows for an engaging user experience.
* **Contact System**: Integrated messaging system for general inquiries and support.

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3, JavaScript (ES6)
* **Backend**: PHP
* **Database**: MySQL
* **Icons/Fonts**: Font Awesome 4.7

## 📂 Database Schema

The system relies on a relational database (MySQL) with the following core tables:
* `customer`: Manages user credentials.
* `tailor`: Stores professional tailor accounts.
* `bookings`: Tracks appointments and schedules.
* `messages`: Stores data from the contact us form.

## 🔧 Installation

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/your-username/fabric-studio.git](https://github.com/your-username/fabric-studio.git)
    ```
2.  **Database Setup**:
    * Open PHPMyAdmin.
    * Create a database named `users`.
    * Import the provided `.sql` files (`customer.sql`, `tailor.sql`, `users.sql`).
3.  **Configure Connection**:
    * Ensure `db_connect.php` matches your local server credentials (usually `localhost`, `root`, and an empty password).
4.  **Run**:
    * Move the project folder to your `htdocs` directory (XAMPP).
    * Navigate to `localhost/fabric-studio/main.html` in your browser.
