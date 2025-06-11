# Product Management API

This project is a simple REST API built with **Node.js**, **Express**, and **MongoDB**. It includes:

- User Registration and Login 
- CRUD operations for a Product (name, price, quantity)

## Setup Instructions

### 1. Clone the Repository

git clone https://github.com/Malkishara/product-management-api.git

cd product-management-api

### 2. Install Dependencies

npm install

### 3. Start MongoDB

Make sure MongoDB is installed and running on your system. MongoDB should run on the default port: mongodb://localhost:27017 .

### 4. Start the Server

npm start


The server will run at: http://localhost:5000 .


## API Endpoints

### User Routes

Register a new user:  POST  /api/auth/register

Login user:  POST  /api/auth/login

###  Product Routes

Create a product: POST /api/products

Get all products: GET /api/products

Get a product by ID: GET /api/products/:id

Update a product: PUT /api/products/:id

Delete a product: DELETE /api/products/:id


## Testing

You can test endpoints using Postman.
