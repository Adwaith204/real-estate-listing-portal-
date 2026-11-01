# 🏡 Real Estate Listing Portal

A web-based real estate management application developed using PHP and MySQL. The project allows users to explore properties for sale and rent, view property details, save favorite properties, calculate mortgage payments, and submit property-related inquiries.

## 📌 Project Overview

The Real Estate Listing Portal provides a platform for browsing and managing real estate listings. It includes user-facing property features and an administrative module for managing listings and reviewing inquiries.

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Local Server:** XAMPP
- **Database Management:** phpMyAdmin

## ✨ Features

### User Module
- User registration and login
- User profile management
- Browse properties for sale and rent
- View detailed property information
- Search and filter properties
- Save favorite properties
- Submit property inquiries
- Contact the administrator
- Mortgage calculator
- Submit home loan applications
- View loan application status

### Admin Module
- Admin login and dashboard
- Add, edit, and delete property listings
- Manage properties for sale and rent
- View registered users
- Review property inquiries
- Manage contact inquiries and replies
- Review home loan applications
- Update loan application status
- View administrative reports and login activity

## 🗄️ Database

The project uses a MySQL database named `real_estate`.

The database includes the following tables:

| Table | Description |
|---|---|
| `admin` | Administrator accounts |
| `buy_properties` | Properties available for sale |
| `rent_properties` | Properties available for rent |
| `register` | User registration information |
| `favourite` | Saved favorite properties |
| `contact_inquiry` | Contact form submissions |
| `property_inquiry` | Property-related inquiries |
| `loan_applications` | Home loan applications |
| `user_logins` | User login activity |

The database export is located in `database/real_estate.sql`.

## ⚙️ Installation and Setup

### Prerequisites

- XAMPP
- PHP
- MySQL or MariaDB
- A web browser

### 1. Clone the Repository

```bash
git clone https://github.com/Adwaith204/real-estate-listing-portal.git
```

### 2. Move the Project

Place the project folder inside your XAMPP `htdocs` directory.

Example:

```text
C:\xampp\htdocs\real-estate-listing-portal\
```

### 3. Start XAMPP

Open the XAMPP Control Panel and start:

- Apache
- MySQL

### 4. Import the Database

1. Open phpMyAdmin in your browser.
2. Create a database named `real_estate`.
3. Select the database.
4. Import `database/real_estate.sql`.

### 5. Configure the Database Connection

Open `conn.php` and configure the database host, username, password, and database name according to your local XAMPP setup.

Do not use production database credentials in a public repository.

### 6. Run the Application

Open your browser and visit:

```text
http://localhost/real-estate-listing-portal/
```

## 📚 Skills Demonstrated

- Frontend web development
- PHP backend development
- MySQL database management
- CRUD operations
- Database connectivity
- Form handling and validation
- User authentication and session handling
- File uploads
- Property search and filtering
- Admin dashboard development
- Git and GitHub

## 🚀 Future Enhancements

- Advanced property filtering and sorting
- Map-based property search
- Email notifications
- Improved mobile responsiveness
- Property comparison functionality
- Improved authentication and password security
- Deployment to a live web server

## 👨‍💻 Developer

**Adwaith K. S.**

BCA Graduate | Aspiring Software Developer

- **GitHub:** [Adwaith204](https://github.com/Adwaith204)
- **LinkedIn:** [Adwaith K. S.](https://www.linkedin.com/in/adwaithh-k-s/)

---

⭐ If you find this project interesting, feel free to explore the repository!
