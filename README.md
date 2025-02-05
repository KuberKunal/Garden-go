# Garden-go
Go Garden is a web application built using Flask, SQLAlchemy, and pytest to provide an interactive platform for gardening enthusiasts. The website serves as an online gardening store and a knowledge hub, allowing users to explore plants, purchase gardening products, and learn best practices for plant care.

*Tech Stack*:

Backend: Flask (Python-based web framework)
Database: SQLAlchemy (ORM for database management)
Frontend: HTML, CSS, JavaScript (optional frameworks like Bootstrap)
Testing: pytest (for unit and integration testing)


*Features*:

1️⃣ User Management
User registration and authentication (login/logout)
Profile management
Role-based access (Admin/User)
2️⃣ Product Management
Categories: Plants, Seeds, Tools, Fertilizers, Pots, etc.
CRUD operations for products (Admin functionality)
Product search and filtering
3️⃣ Shopping Cart & Orders
Add, update, and remove items from the cart
Checkout process with order confirmation
Order history and tracking
4️⃣ Gardening Blog & Knowledge Base
Articles and tips on plant care
User comments and discussions
5️⃣ Wishlist & Recommendations
Save favorite plants and products
AI-powered recommendations (future scope)
6️⃣ Secure Payment Gateway
Integration with Razorpay/Stripe (future enhancement)
7️⃣ Testing with pytest
Unit tests for models and database interactions
Functional tests for routes and API responses
Integration tests for user and order workflows


Database Schema (Using SQLAlchemy)

User: id, name, email, password, role
Product: id, name, category_id, price, stock, description
Category: id, name
Cart: id, user_id, total_price
CartItem: id, cart_id, product_id, quantity
Order: id, user_id, total_price, status, created_at
OrderItem: id, order_id, product_id, quantity
Blog: id, title, content, user_id, created_at


Current Progress:

✅ Database schema designed using SQLAlchemy
✅ Basic CRUD operations for products & categories implemented
✅ User authentication system working
✅ pytest setup and initial test cases written

