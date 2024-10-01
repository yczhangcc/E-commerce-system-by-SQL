# E-commerce Database System - README

## Project Overview

This project is an **E-commerce Shopping Platform Database** designed to support an online shopping system. The platform allows users to browse products, add them to a shopping cart, and complete purchases. Administrators can manage products, users, and orders efficiently.

The database system is developed to:
- **Store and manage** data related to users, products, orders, and shopping carts.
- Provide a robust platform for **managing e-commerce operations** for both consumers and administrators.

### Key Features:
- 🛍️ **User Registration & Login**: Users can create an account, log in, and manage their shopping activities.
- 📦 **Product Browsing**: Users can browse products categorized by type, price, and availability.
- 🛒 **Shopping Cart Management**: Users can add items to their cart, modify quantities, or remove items.
- 💳 **Order Management**: Orders are generated upon checkout, and users can view their order history.
- 👤 **Administrator Capabilities**: Admins can manage products, user accounts, and track orders.

## System Components

### 1. **Database Design**
The database consists of six primary tables:
- **users**: Stores user information (e.g., ID, name, email, etc.).
- **managers**: Stores administrator details.
- **products**: Contains product details (e.g., ID, name, price, inventory).
- **categories**: Stores product category information.
- **orders**: Stores order information (e.g., user ID, product ID, quantity, payment status).
- **carts**: Stores shopping cart details (e.g., user ID, product ID, quantity).

### 2. **Functionality**
- **User Interface**: Users can register, log in, view products, manage their shopping carts, and complete purchases.
- **Admin Interface**: Administrators can add or remove products, manage user data, and track order statuses.
- **Shopping Cart**: Users can view and edit items in their cart before finalizing the purchase.
- **Order Management**: After placing an order, users can track the payment status and order history.

## Security and Integrity
- **Role-Based Access Control (RBAC)**: Ensures that users and administrators have distinct permissions. Users can only access their own data and place orders, while administrators can manage the entire platform.
- **Data Integrity Constraints**: Ensures data consistency by enforcing primary key, foreign key, and unique constraints across tables.

## Installation

To set up the e-commerce platform:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/ecommerce-database.git
    ```
2. **Database Setup**:
   - Import the provided SQL schema to create the required database tables.
   - Load initial data by executing the data-loading scripts.

3. **Application Setup**:
   - Configure the application to connect to the database.
   - Run the server and access the platform via the localhost URL.

4. **Admin Account**:
   - Create an initial admin account for product and order management.

## Usage

- **Users**: 
  - Register and log in to start shopping.
  - Browse products by category and add them to the shopping cart.
  - Review your cart and place orders.

- **Admins**: 
  - Log in to manage the platform, including adding/removing products and monitoring orders.
  - Use the admin panel to view customer details and update the product catalog.

## Contributions

If you'd like to contribute, please fork the repository and submit a pull request with your changes.

---

This project aims to deliver a seamless and user-friendly e-commerce experience by integrating efficient database management, user security, and a responsive shopping interface.

---

Feel free to customize the "Contributions" section if your project is hosted on GitHub and open for contributions.
