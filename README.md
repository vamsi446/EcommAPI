Overview
This is a simple e-commerce application that allows two types of users, customers, and sellers, to interact with the platform. Users can perform various actions such as adding, deleting, and updating products. The application uses Multer for file upload, JWT for user authentication, Winston logger for logging, Express routes for handling HTTP requests, MongoDB for database storage, Mongoose for schema modeling, Dotenv for managing environment variables, and Swagger for API documentation.

Features
1.User Authentication
Users (both customers and sellers) are required to authenticate using JSON Web Tokens (JWT).
2.Product Management
Sellers can add, delete, and update products. Product information includes details like name, description, price, and images (uploaded using Multer).
3.Shopping Cart
Customers can add products to their shopping cart.
4.Order Placement
Users can place orders, and the application uses MongoDB transactions to maintain data integrity while placing orders.
5.Like Products/Category
Users can like products or entire categories.
6.Reviews
Customers can add reviews for products.


Tech Stack
Node.js: Runtime environment.
Express: Web application framework.
MongoDB: Database for storing product, user, and order information.
Mongoose: ODM library for MongoDB.
Multer: Middleware for handling file uploads.
JWT (JSON Web Tokens): Authentication mechanism.
Winston: Logger for logging events and errors.
Dotenv: Module for managing environment variables.
Swagger: Documentation tool for API documentation.

Error Handling
The application handles errors gracefully and logs them using the Winston logger.