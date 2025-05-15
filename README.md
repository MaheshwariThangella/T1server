# T1server
# Node.js Express Server with MongoDB (Mongoose)

This project is a simple Express server connected to MongoDB using Mongoose. It provides a backend API and data models using Mongoose schemas.

---

## Project Structure

project-root/
│
├── server.js # Main server file (Express app)
├── models/
│ └── User.js # Example Mongoose schema file
├── package.json
└── README.md

---

## Prerequisites

- [Node.js](https://nodejs.org/) installed
- [MongoDB](https://www.mongodb.com/) installed and running locally or use a MongoDB Atlas URI

---

## Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
npm install
MONGO_URI=mongodb://localhost:27017/your-db-name
PORT=3000
npm start
