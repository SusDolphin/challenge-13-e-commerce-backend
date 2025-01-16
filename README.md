# E-Commerce Backend

## Description
A robust backend API for an e-commerce platform built with Express.js and Sequelize ORM. This application provides RESTful API endpoints to manage products, categories, and tags in an e-commerce database.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [License](#license)

## API Endpoints

### Tags
- `GET /api/tags` - Get all tags
- `GET /api/tags/:id` - Get a single tag by ID
- `POST /api/tags` - Create a new tag
- `PUT /api/tags/:id` - Update a tag
- `DELETE /api/tags/:id` - Delete a tag

### Products
- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get a single product by ID
- `POST /api/products` - Create a new product
- `PUT /api/products/:id` - Update a product
- `DELETE /api/products/:id` - Delete a product

### Categories
- `GET /api/categories` - Get all categories
- `GET /api/categories/:id` - Get a single category by ID
- `POST /api/categories` - Create a new category
- `PUT /api/categories/:id` - Update a category
- `DELETE /api/categories/:id` - Delete a category

## Technologies Used
- Node.js
- Express.js
- MySQL2
- Sequelize ORM
- dotenv

## License
This project is licensed under the [MIT License](LICENSE).
