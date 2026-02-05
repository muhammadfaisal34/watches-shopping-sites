# Watches Shopping Site

This project is a PHP-based e-commerce platform designed for purchasing watches. It includes both user-facing and admin-facing functionalities, allowing users to browse products, manage their shopping cart, and complete purchases, while administrators can manage products and brands.

## Features

### User Features
- **Home Page**: Browse available watches.
- **Product Details**: View detailed information about each product.
- **Shopping Cart**: Add, update, or remove items.
- **Checkout**: Complete the purchase process.
- **User Authentication**: Login and registration functionality.

### Admin Features
- **Add Products**: Add new watches to the catalog.
- **Update Products**: Modify existing product details.
- **Manage Brands**: Add and manage watch brands.
- **View Product Details**: Access detailed product information.
- **Admin Authentication**: Secure login for administrators.

## Project Structure

### Root Directory
- `index.php`: Main entry point for users.
- `cart.php`: Handles shopping cart operations.
- `checkout.php`: Manages the checkout process.
- `products.php`: Displays the product catalog.
- `config.php`: Configuration settings.
- `demo.sql`: Database schema and sample data.
- `README.md`: Project documentation.

### Admin Directory
- `addbrand.php`: Add new brands.
- `addproduct.php`: Add new products.
- `config.php`: Admin-specific configuration.
- `index.php`: Admin panel entry point.
- `productdetails.php`: View product details.
- `queries_admin.txt`: Admin-related SQL queries.
- `takedown.php`: Remove products or brands.
- `update.php`: Update product or brand details.

### CSS Directory
- Contains stylesheets for various pages, such as `home.css`, `cart.css`, and `product.css`.

### Images Directory
- `brandimgs/`: Images for watch brands.
- `productimgs/`: Images for products.

### Login and Register Directory
- `login.php`: User login functionality.
- `register.php`: User registration functionality.
- `logout.php`: Logout functionality.
- `config.php`: Configuration for authentication.
- `Queries.txt`: SQL queries for user authentication.

## Database
- The `demo.sql` file contains the database schema and sample data for setting up the project.

## Setup Instructions
1. Clone the repository to your local machine.
2. Place the project in your web server's root directory (e.g., `htdocs` for XAMPP).
3. Import the `demo.sql` file into your MySQL database.
4. Update the `config.php` files with your database credentials.
5. Start your web server and navigate to the project in your browser.

## Requirements
- PHP 7.4 or higher
- MySQL 5.7 or higher
- A web server (e.g., XAMPP, WAMP, or LAMP)

## License
This project is licensed under the MIT License. You are free to use and modify it as needed.

---

For any issues or contributions, please contact the project maintainers.
