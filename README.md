# PH Tour Management System - Backend

Backend API for the **PH Tour Management System**, built with **Node.js**, **Express**, **MongoDB**, and **Zod** for validation.

---

## 🚀 Features

- **RESTful API** for managing tours, bookings, and users.
- **Data Validation** using **Zod** for secure and type-safe request handling.
- **MongoDB Integration** for flexible and scalable database management.
- **Authentication & Authorization** for secure access (JWT-based).
- **CRUD Operations** for tours, bookings, and user management.
- **Error Handling & Logging** for robust backend operations.
- **Modular Architecture** for maintainable and scalable code.

---

## 🛠 Tech Stack

- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB / Mongoose
- **Validation:** Zod
- **Authentication:** JWT (JSON Web Token)
- **Version Control:** Git & GitHub
- **Environment Variables:** dotenv

---

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Mahabub2030/ph-tour-management-system-backend.git
cd ph-tour-management-system-backend
```

Install dependencies:

npm install
or
bun install
or
yearn install

Create a .env file with the following variables:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Run the server (development mode):

npm run dev

Server should run at http://localhost:5000
.

```base

📂 Project Structure
ph-tour-management-system-backend/
│
├── src/
│   ├── controllers/      # Route controllers (business logic)
│   ├── models/           # Mongoose models
│   ├── routes/           # Express routes
│   ├── middlewares/      # Auth, error handling, etc.
│   ├── utils/            # Helper functions & Zod schemas
│   ├── config/           # DB & environment configuration
│   └── server.js         # Entry point
├── package.json
├── .env
└── README.md
```

```base

⚡ API Endpoints
Users

POST /api/users/register – Register a new user

POST /api/users/login – Login a user

GET /api/users/profile – Get user profile (protected)

Tours

GET /api/tours – Get all tours

POST /api/tours – Create a new tour (admin)

GET /api/tours/:id – Get tour by ID

PUT /api/tours/:id – Update tour (admin)

DELETE /api/tours/:id – Delete tour (admin)

Bookings

POST /api/bookings – Create a booking

GET /api/bookings – Get all bookings (admin)

GET /api/bookings/:id – Get booking by ID

PUT /api/bookings/:id – Update booking (admin)

DELETE /api/bookings/:id – Delete booking (admin)

All endpoints support JSON requests and responses.

🧩 Key Libraries
Library	Purpose
Express	Web framework
Mongoose	MongoDB object modeling
Zod	Schema validation
bcryptjs	Password hashing
jsonwebtoken	JWT authentication
dotenv	Environment variable management
nodemon	Development server auto-restart
🤝 Contributing

Fork the repository

Create a feature branch: git checkout -b feature/YourFeature

Commit your changes: git commit -m "Add some feature"

Push to the branch: git push origin feature/YourFeature

Open a pull request

📄 License

This project is licensed under the MIT License.

Made with ❤️ by Mahabub Alam
```
