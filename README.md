🛒 E-Commerce Microservices Platform

A scalable e-commerce backend built using Node.js and Microservices Architecture. The application is divided into independent services such as Authentication, Product, Order, Payment, and AI Assistant. Each service can be developed, deployed, and maintained independently.

The main goal of this project is to learn how microservices communicate, improve scalability, and build a production-style backend.

✨ Features
User Authentication using JWT
Product Management
Order Management
Payment Integration
AI Shopping Assistant
API Gateway
Independent Microservices
RESTful APIs
Secure Authentication
Error Handling
Environment Configuration
Scalable Project Structure

🏗 Architecture
                Client
                   │
                   ▼
             API Gateway
                   │
 ┌─────────────────┼──────────────────┐
 │                 │                  │
 ▼                 ▼                  ▼
Auth Service   Product Service   Order Service
                   │                  │
                   ▼                  ▼
             Payment Service     AI Buddy Service
                   │
                   ▼
                MongoDB

Each service works independently and communicates through APIs or message queues when required.

🛠 Tech Stack
Backend
Node.js
Express.js
MongoDB
Mongoose
Authentication
JWT
bcrypt
Communication
REST APIs
RabbitMQ
Payment
Razorpay
AI
Google Gemini API
Dev Tools
Docker
Git
GitHub
Postman

🚀 Services
Authentication Service
User Registration
User Login
JWT Authentication
Password Encryption
Product Service
Add Product
Update Product
Delete Product
View Products
Order Service
Create Orders
Manage Orders
Update Order Status
Payment Service
Razorpay Payment Integration
Payment Verification
AI Buddy Service
AI-powered customer assistance
Product-related questions
Shopping guidance using Google Gemini API
