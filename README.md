# Inventory Management Backend

A Node.js backend application for managing inventory, built with Express.js, JWT authentication, and MongoDB. This project provides RESTful APIs for user authentication and inventory operations.

## 🚀 Features

- User registration & login with JWT authentication
- CRUD operations for inventory items
- MongoDB with Mongoose ODM
- Environment-based configuration with dotenv
- Organized folder structure for scalability

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB & Mongoose
- JSON Web Tokens (JWT)
- dotenv
- bcryptjs
- nodemon (dev)

## 📁 Project Structure

backend_inventory/
│
├── controllers/ # Logic for each route
├── models/ # Mongoose schemas
├── routes/ # API endpoints
├── middlewares/ # Auth and error handling
├── utils/ # Helper functions
├── app.js # Main server setup
├── .env # Environment variables
├── package.json # Dependencies
└── README.md # Project documentation

## ⚙️ Environment Variables

Create a `.env` file in the root with:

```env



# Clone the repository
git clone https://github.com/your-username/backend_inventory.git
cd backend_inventory

# Install dependencies
npm install

# Start the server
npm run dev

Testing the API
Use tools like Postman to test:

POST /api/v1/auth/register

POST /api/v1/auth/login

GET /api/v1/items

POST /api/v1/items

PUT /api/v1/items/:id

DELETE /api/v1/items/:id
