# ZestKart - Software Requirements Specification (SRS) Document

### Table of Contents

1. [Introduction](#introduction)
    - [1.1 Purpose](#11-purpose)
    - [1.2 Document Conventions](#12-document-conventions)
    - [1.3 Intended Audience](#13-intended-audience)
    - [1.4 Scope](#14-scope)
    - [1.5 References](#15-references)

2. [Overall Description](#overall-description)
    - [2.1 Product Perspective](#21-product-perspective)
    - [2.2 Product Features](#22-product-features)
        - [2.2.1 Customer Features](#221-customer-features)
        - [2.2.2 Seller Features](#222-seller-features)
        - [2.2.3 Admin Features](#223-admin-features)
    - [2.3 User Characteristics](#23-user-characteristics)
    - [2.4 Constraints](#24-constraints)

3. [Specific Requirements](#specific-requirements)
    - [3.1 Functional Requirements](#31-functional-requirements)
    - [3.2 Non-Functional Requirements](#32-non-functional-requirements)

4. [Data Model](#data-model)
    - [4.1 Entities and Attributes](#41-entities-and-attributes)
    - [4.2 Relationships](#42-relationships)

5. [User Interface](#user-interface)
    - [5.1 Design Principles](#51-design-principles)

6. [Appendices](#appendices)
    - [6.1 Technical Specifications](#61-technical-specifications)

## Introduction

### 1.1 Purpose

This document outlines the software requirements for the development of ZestKart, a comprehensive e-commerce application. It defines the scope, functionalities, and constraints of ZestKart, serving as a guide for the development team and a reference point for all stakeholders.

### 1.2 Document Conventions

This document will use the following conventions:

* **Shall:** Indicates a mandatory requirement.
* **Should:** Indicates a desirable but not mandatory requirement.
* **User:** Refers to any individual interacting with the ZestKart application.
* **Admin:** Refers to authorized personnel managing the backend of the application.

### 1.3 Intended Audience

This SRS document is intended for use by the following stakeholders:

* Project sponsors
* Project manager
* Development team
* Testing team
* Marketing team

### 1.4 Scope

The ZestKart application aims to provide a platform for businesses and individuals to sell products online. The application will encompass all necessary features for product listing, order management, payment processing, customer support, and marketing.

### 1.5 References
- [SWEBOK Guide](https://www.computer.org/web/swebok)
- [IEEE Standard 829-2008](https://standards.ieee.org/standard/829-2008.html)

## Overall Description

### 2.1 Product Perspective

ZestKart will be a web-based platform accessible through various devices such as desktops, laptops, tablets, and smartphones. It will provide a user-friendly interface for both customers and sellers.

### 2.2 Product Features

#### 2.2.1 Customer Features

* **User Registration and Management:**
    * Users shall be able to register and manage their accounts.
    * Users should be able to log in via social media accounts.
    * Users shall be able to view and edit their profile information.
* **Product Browsing and Search:**
    * Users shall be able to browse products by category, sub-category, and filters.
    * Users shall be able to search for products using keywords.
    * The application should provide relevant search suggestions.
* **Product Details:**
    * Users shall be able to view detailed product descriptions, images, reviews, and ratings.
* **Shopping Cart:**
    * Users shall be able to add and remove products from their shopping cart.
    * Users shall be able to view and edit the quantity of each product in their cart.
* **Checkout Process:**
    * Users shall be able to proceed to checkout as a guest or logged-in user.
    * Users shall be able to enter shipping and billing information securely.
    * Users shall be able to select from various shipping options.
* **Payment Processing:**
    * ZestKart shall support multiple payment gateways (e.g., credit/debit cards, PayPal, Stripe).
    * ZestKart shall ensure secure payment processing.
* **Order Tracking:**
    * Users shall be able to track the status of their orders.
    * Users shall receive order confirmation and shipping notifications.
* **Customer Support:**
    * Users shall be able to contact customer support through various channels (e.g., live chat, email, phone).
* **Wishlist:**
    * Users should be able to create and manage a wishlist of products.
* **Reviews and Ratings:**
    * Users should be able to submit reviews and ratings for purchased products.

#### 2.2.2 Seller Features

* **Seller Registration and Management:**
    * Sellers shall be able to register and manage their seller accounts.
    * Sellers shall be able to provide business information and product listings.
* **Product Listing Management:**
    * Sellers shall be able to add, edit, and remove product listings.
    * Sellers shall be able to set product prices, inventory levels, and shipping options.
* **Order Management:**
    * Sellers shall be able to view and manage customer orders.
    * Sellers shall be able to update order status and generate shipping labels.
* **Sales Analytics and Reports:**
    * Sellers should be able to access their respective sales data and generate reports.
* **Inventory Management:**
    * Sellers should be able to manage their inventory levels and receive low stock notifications.

#### 2.2.3 Admin Features

* **User Management:**
    * Admins shall be able to manage user accounts (both customers and sellers).
* **Product Catalog Management:**
    * Admins shall be able to manage product categories and attributes.
* **Order Management:**
    * Admins shall be able to view and manage all orders placed on ZestKart.
* **Payment and Commission Management:**
    * Admins shall be able to manage payment gateways and set commission rates.
* **Marketing and Promotions:**
    * Admins shall be able to create and manage marketing campaigns, discounts, and promotional offers.
* **Content Management System (CMS):**
    * Admins should be able to manage website content, including pages, images, and blog posts.
* **Analytics and Reporting:**
    * Admins shall be able to access comprehensive analytics and generate reports on various aspects of ZestKart.

### 2.3 User Characteristics

* **Customers:** Individuals with varying levels of technical expertise who are looking to purchase products online.
* **Sellers:** Businesses or individuals who wish to sell products online, with varying levels of technical expertise.
* **Admins:** Technical personnel responsible for managing and maintaining ZestKart.

### 2.4 Constraints

* ZestKart shall be developed using open-source technologies.
* ZestKart shall be hosted on a cloud-based platform.
* ZestKart shall comply with all relevant data privacy and security regulations.

## Specific Requirements

### 3.1 Functional Requirements

* **User Authentication:** ZestKart shall provide secure user authentication and authorization mechanisms.
* **Product Search and Filtering:** ZestKart shall provide robust search and filtering options to allow users to find desired products easily.
* **Shopping Cart and Checkout:** ZestKart shall facilitate a seamless shopping experience with a user-friendly shopping cart and checkout process.
* **Secure Payment Processing:** ZestKart shall integrate with reputable payment gateways to ensure secure and reliable payment transactions.
* **Order Management:** ZestKart shall provide comprehensive order management capabilities, allowing users to track their orders and sellers to fulfill orders efficiently.
* **Customer Support:** ZestKart shall offer various customer support channels to address user queries and issues promptly.

### 3.2 Non-Functional Requirements

* **Performance:** ZestKart shall be responsive and provide fast loading times.
* **Security:** ZestKart shall prioritize data security and implement measures to prevent unauthorized access and data breaches.
* **Usability:** ZestKart shall have a user-friendly and intuitive interface, making it easy for users of all technical levels to navigate and interact with the platform.
* **Reliability:** ZestKart shall be stable and reliable, minimizing downtime and ensuring continuous availability.
* **Scalability:** ZestKart shall be designed to accommodate future growth in terms of user base, product listings, and transaction volume.

## Data Model

The ZestKart application will utilize a relational database management system (RDBMS) to store and manage data. The following entity-relationship diagram (ERD) illustrates the proposed database schema:

![image](https://github.com/SWENGG4Y2024/SWENGG4Y2024Team01/assets/59111478/6a110279-6f06-4c7b-ad1f-2753b4cca142)


### 4.1 Entities and Attributes

#### Users

* user_id (Primary Key)
* first_name
* last_name
* email (Unique)
* password_hash
* address
* city
* state
* zip_code
* phone_number
* user_type (Customer, Seller, Admin)
* created_at
* updated_at

#### Products

* product_id (Primary Key)
* seller_id (Foreign Key referencing Users)
* category_id (Foreign Key referencing Categories)
* name
* description
* price
* stock_quantity
* image_urls (Comma-separated list)
* average_rating (Calculated)
* created_at
* updated_at

#### Categories

* category_id (Primary Key)
* name
* parent_category_id (Foreign Key referencing Categories - for subcategories)

#### Orders

* order_id (Primary Key)
* user_id (Foreign Key referencing Users)
* order_date
* total_amount
* shipping_address
* billing_address
* payment_status (Pending, Paid, Failed)
* order_status (Processing, Shipped, Delivered, Cancelled)

#### Order Items

* order_item_id (Primary Key)
* order_id (Foreign Key referencing Orders)
* product_id (Foreign Key referencing Products)
* quantity
* price_per_unit

#### Reviews

* review_id (Primary Key)
* user_id (Foreign Key referencing Users)
* product_id (Foreign Key referencing Products)
* rating (1-5 stars)
* comment
* created_at

#### Payments

* payment_id (Primary Key)
* order_id (Foreign Key referencing Orders)
* transaction_id (Unique identifier from payment gateway)
* payment_method
* amount
* payment_date

### 4.2 Relationships

* **One-to-Many:** A User can have multiple Orders. A Product can belong to one Category. An Order can have multiple Order Items. A Product can have multiple Reviews.
* **Many-to-One:** An Order Item belongs to one Order and one Product. A Review belongs to one User and one Product. A Payment belongs to one Order.

## User Interface

### 5.1 Design Principles

* **Clean and Modern:** The user interface will adopt a clean, modern aesthetic with a focus on visual hierarchy and clear typography.
* **User-Friendly:** The layout will be intuitive and easy to navigate, ensuring a seamless user experience for all user roles on ZestKart.
* **Responsive Design:** ZestKart will be fully responsive across various screen sizes and devices.
* **Accessibility:** The UI will adhere to accessibility guidelines (WCAG) to ensure usability for individuals with disabilities.

## Appendices

### 6.1 Technical Specifications

* **Programming Languages:** Java, Javascript, Python, Node.js
* **Frameworks and Libraries:** Flask, Express.js, React, Springboot
* **Database:** MySQL, PostgreSQL, MongoDB, etc.
* **Cloud Platform:** AWS, Google Cloud, Azure, etc.
