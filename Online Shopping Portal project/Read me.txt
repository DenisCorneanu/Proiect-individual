# Online Shopping Portal

A full-stack e-commerce web application built with PHP, MySQL, JavaScript/jQuery, HTML and CSS. The platform allows users to browse products across multiple categories, manage a shopping cart and wishlist, and complete purchases through a multi-step checkout process.

---

## Features

- **Product Browsing** — Navigate through categories (Books, Electronics, Furniture, Fashion) with search and category filtering
- **Product Details** — Dedicated pages with descriptions, pricing, availability, delivery fees, and user reviews & ratings
- **Shopping Cart** — Add/remove products, manage quantities, view recommended products
- **Wishlist** — Save favourite products for later
- **Checkout Flow** — Billing & shipping address form, payment method selection, and order confirmation
- **User Accounts** — Register, login, update personal data, manage delivery addresses
- **Order Management** — View order history, track orders, manage pending orders
- **Admin Panel** — Full backend management interface

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | HTML, CSS, JavaScript, jQuery |
| Backend | PHP |
| Database | MySQL |

---

## Project Structure

```
shopping/
├── admin/                    # Admin panel
├── assets/                   # Static assets
├── css/                      # Stylesheets
├── js/                       # JavaScript files
├── includes/                 # Reusable PHP components
├── layouts/                  # Page layout templates
├── SQL file/                 # Database schema
├── index.php                 # Homepage
├── login.php                 # Authentication
├── my-cart.php               # Shopping cart
├── my-wishlist.php           # Wishlist
├── product-details.php       # Product detail page
├── bill-ship-addresses.php   # Checkout - shipping info
├── payment-method.php        # Checkout - payment
├── order-details.php         # Checkout - confirmation
├── my-account.php            # User profile
├── order-history.php         # Past orders
└── track-order.php           # Order tracking
```

---

## Installation & Setup

1. Download the ZIP file and extract it
2. Copy the `shopping` folder into your local server root directory:
   - XAMPP → `xampp/htdocs/`
   - WAMP → `wamp/www/`
   - LAMP → `var/www/html/`
3. Open PHPMyAdmin at `http://localhost/phpmyadmin`
4. Create a new database named `shopping`
5. Import the SQL file located in the `SQL file/` folder
6. Run the application:
   - Frontend → `http://localhost/shopping`
   - Admin Panel → `http://localhost/shopping/admin`

### Admin Credentials

| Field | Value |
|-------|-------|
| Username | `admin` |
| Password | `admin` |

---

*Developed as an individual university project at Facultatea de Informatică, UVT Timișoara.*
