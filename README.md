# Simple E-commerce Project

A basic e-commerce application built with MERN stack (MongoDB, Express.js, React, Node.js) and Zustand for state management.

## Features

- Create, Read, Update, and Delete (CRUD) products
- Real-time UI updates using Zustand store
- MongoDB database integration
- RESTful API endpoints

## Tech Stack

- Frontend:
  - React.js
  - Zustand (State Management)
  - Fetch API for HTTP requests

- Backend:
  - Node.js
  - Express.js
  - MongoDB with Mongoose
  
## Project Structure
simple-ecommerce/ ├── frontend/ │ └── src/ │ └── store/ │ └── product.js └── backend/ ├── config/ │ └── db.js ├── controllers/ │ └── product.controller.js ├── models/ │ └── product.model.js ├── routes/ │ └── product.route.js └── server.js


## API Endpoints

- GET `/api/products` - Get all products
- POST `/api/products` - Create a new product
- PUT `/api/products/:id` - Update a product
- DELETE `/api/products/:id` - Delete a product

## Setup Instructions

1. Clone the repository
2. Install dependencies:
```bash
cd frontend && npm install
cd backend && npm install

This README.md provides:
1. Project overview
2. Features list
3. Technology stack
4. Project structure
5. API endpoints
6. Setup instructions


deployment on render : https://e-commerce-mn4f.onrender.com 




