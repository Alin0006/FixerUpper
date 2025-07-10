
I chose to name the project fixerupper_db because I had already used FixerUpper for my first attempt, where the CSS styles would not apply correctly, regardless of me trying to repair it. 
I didn't want to lose time by losing my progress and therefore started an new project from scratch with the name fixerupper_db keeping the original FixerUpper project as a backup, 
in case the new version didn't work out.


FixerUpper E-Commerce Website

A complete e-commerce website for FixerUpper, a hardware appliances company based in Newcastle. This project demonstrates the transition from "Brick & Mortar" to "Click & Mortar" business model.

 Features

 Customer Features
- Product Catalog - Browse hardware appliances by category (Tools, Appliances, Garden, Safety)
- User Registration & Login - Secure account creation and authentication
- Shopping Cart - Add/remove products, quantity management
- Checkout System - Complete order placement with delivery options
- Order Tracking - View order history and status updates
- User Dashboard - Personal account management
- Contact System - Send inquiries to the company

Admin Features
- Admin Dashboard - Overview statistics and quick actions
- Product Management - Add, edit, delete, and manage product inventory
- Order Management - View and update order statuses
- Customer Management - View and manage user accounts
- Message Center - Review and respond to customer inquiries

Technology Stack

- Frontend: HTML5, CSS3, JavaScript
- Backend: PHP 
- Database: MySQL
- Server: Apache (XAMPP)
- Security: CSRF protection, SQL injection prevention, input validation

Requirements

- XAMPP (Apache + MySQL + PHP 8.0+)
- Web browser: I test the website only in Chrome


Access Website

   - Frontend: `http://localhost/fixerupper_db/`
   - Admin Panel: `http://localhost/fixerupper_db/admin.php`

Default Login Credentials

Admin Access
- Email: admin
- Password: admin

Sample Customer Account
- Email: john@example.com
- Password: admin

Project Structure


fixerupper_db/
├── css/
│   └── style.css               Main stylesheet
├── js/
│   └── main.js                JavaScript functionality
├── images/                    Product images and assets
├── index.php                  Homepage
├── config.php                Database configuration
├── login.php                 User authentication
├── register.php              User registration
├── products.php              Product catalog
├── cart.php                  Shopping cart
├── checkout.php              Order placement
├── dashboard.php             User dashboard
├── admin.php                 Admin dashboard
├── admin_products.php        Product management
├── admin_orders.php          Order management
├── admin_messages.php        Customer messages
├── admin_users.php           User management
├── contact.php               Contact form
├── about.php                 Company information
└── database.sql              Database structure and sample data


 Security Features

- SQL Injection Protection - Parameterized queries and input sanitization
- CSRF Protection - Token-based request validation
- XSS Prevention - Output escaping and input validation
- Session Management - Secure session handling
- Role-based Access - Admin and customer permission levels

 Database Schema

 Main Tables
- users - Customer and admin accounts
- products - Product catalog with categories and inventory
- orders - Order information and tracking
- order_items - Individual items within orders
- contact_messages - Customer inquiries

 Usage

For Customers
1. Browse products on the homepage
2. Register for an account or login
3. Add products to cart
4. Complete checkout process
5. Track orders in dashboard

 For Administrators
1. Login with admin credentials
2. Manage products (add/edit/delete)
3. Process orders and update statuses
4. View customer messages
5. Manage user accounts

 Key Business Features

- Inventory Management - Real-time stock tracking
- Order Processing - Complete order lifecycle management
- Customer Service - Built-in messaging system
- Analytics - Sales and order statistics
- Responsive Design - Mobile-friendly interface

Contact Information

FixerUpper Hardware
- Address: 123 Hardware Street, Newcastle, NE1 4AB, UK
- Phone: 0191 123 4567
- Email: info@fixerupper.co.uk

 License

This project is developed by Alin Dragomir, for educational purposes as part Secure Website Development module assessment 2.


 Future Enhancements

- Payment gateway integration
- Email notifications for orders
- Advanced product search and filtering
- Customer reviews and ratings
- Multi-language support
- SEO optimization

---

Note: This is a prototype website developed to demonstrate e-commerce functionality and security implementations for academic purposes.
