# E-Commerce API

This API provides functionality for managing products, orders, and users in an e-commerce system.

## Table of Contents

- [Introduction](#introduction)
- [API Endpoints](#api-endpoints)
  - [Products](#products)
  - [Orders](#orders)
  - [Users](#users)
- [Registering a New User](#registering-a-new-user)
- [Logging In](#logging-in)
- [Postman Collection](#postman-collection)
- [Swagger (OpenAPI) Specification](#swagger-openapi-specification)

## Introduction

This API is designed to handle various operations related to an e-commerce platform, including managing products, orders, and users.

## API Endpoints

### Products

- **GET /api/v1/products:** Get all products.
- **GET /api/v1/products/:id:** Get a product by ID.
- **POST /api/v1/products:** Create a new product.
- **PUT /api/v1/products/:id:** Update a product by ID.
- **DELETE /api/v1/products/:id:** Delete a product by ID.
- **PUT /api/v1/products/gallery-images/:id:** Update gallery images for a product.
- **GET /api/v1/products/get/featured/:count:** Get a specified number of featured products.
- **GET /api/v1/products/get/count:** Get the count of products.

### Orders

- **GET /api/v1/orders:** Get all orders.
- **GET /api/v1/orders/:id:** Get an order by ID.
- **POST /api/v1/orders:** Create a new order.
- **PUT /api/v1/orders/:id:** Update an order by ID.
- **DELETE /api/v1/orders/:id:** Delete an order by ID.
- **GET /api/v1/orders/get/count:** Get the count of orders.

### Users

- **GET /api/v1/users:** Get all users.
- **GET /api/v1/users/:id:** Get a user by ID.
- **POST /api/v1/users:** Create a new user.
- **PUT /api/v1/users/:id:** Update a user by ID.
- **DELETE /api/v1/users/:id:** Delete a user by ID.
- **GET /api/v1/users/get/count:** Get the count of users.
- **POST /api/v1/users/register:** Register a new user.
- **POST /api/v1/users/login:** Log in and get an authentication token.

## Registering a New User

To register a new user, make a POST request to the endpoint:
