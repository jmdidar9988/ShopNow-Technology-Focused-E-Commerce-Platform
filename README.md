# ShopNow-Technology-Focused-E-Commerce-Platform
ShopNow is a technology-focused e-commerce web application that simulates a real-world online shopping experience. The platform allows users to browse, purchase, and manage technology products such as gadgets, accessories, and electronic devices. It is built using Flask for the backend and MySQL for the database, managed through XAMPP.

The system supports two main user roles: customers and administrators. Customers can browse products, manage shopping carts, place orders, and track purchases. Administrators can manage products, orders, and overall system operations through a dedicated admin dashboard. The project demonstrates secure authentication, normalized database design, and real-world e-commerce workflows.

## Features
User Features

- Secure user registration, login, and logout
- Role-based access control (Customer and Admin)
- Browse and view technology products with detailed information
- Real-time stock availability
- Shopping cart management (add, update, remove items)
- Checkout and order placement with simulated payment handling
- Order history and order status tracking
- Responsive user interface for desktop and mobile devices

## Admin Features
- Secure admin authentication
- Product management (add, update, delete products)
- Manage product price, stock, category, and images
- Admin dashboard with system overview of products and orders

## Database Design
The application uses a MySQL relational database with a normalized schema to ensure data integrity and scalability.

## Database Tables
- Users – Stores customer and admin account information.
- Categories – Groups technology products logically.
- Products – Stores product details such as name, price, stock, and description.
- Product_Images – Supports multiple images per product.
- Carts – Represents active shopping carts per user.
- Cart_Items – Links carts with products and quantities.
- Orders – Records confirmed purchases and order status.
- Order_Items – Stores products purchased within each order.
- Payments – Tracks simulated payment details.

## Technologies Used

Frontend:
- HTML
- CSS
- JavaScript
- Bootstrap

Backend:
- Flask (Python)
- SQLAlchemy ORM
- Flask-Login
- Flask-WTF (CSRF Protection)

Database and Environment:
- MySQL
- XAMPP (Apache and MySQL)
- phpMyAdmin

## Team Member: 
Md. Masudul Hasan Akib
- https://github.com/ak1bhasan
