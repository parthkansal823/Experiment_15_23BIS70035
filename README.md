# E-commerce Catalog with Nested Documents (MongoDB & Node.js)

## Project Overview
This project demonstrates a simple e-commerce catalog using **Node.js**, **Express**, and **MongoDB** with **nested documents** for product variants.  
Each product has fields like `name`, `price`, `category`, and an array of `variants` containing `color`, `size`, and `stock`.

## Features
- Add a new product with multiple variants
- Retrieve all products
- Filter products by category
- Filter products by variant color

## Prerequisites
- Node.js installed
- MongoDB installed and running locally (or MongoDB Atlas account)
- Postman (for API testing)

## Installation & Setup
1. Install all the dependencies that a project needs
```bash
npm install
```
2. Start MongoDB (if using local MongoDB):
```bash
mongod
```
3. Run the server:
```bash
node server.js
```

