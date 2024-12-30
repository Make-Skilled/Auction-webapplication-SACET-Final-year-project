# Auction Web Application - SACET Final Year Project

This project is an auction web application designed and developed as part of the final year project at SACET. It features a React-based frontend and a Node.js/Express backend, providing seamless interactions for users and administrators.

---

## 🛠 Prerequisites

Before starting, ensure you have the following installed on your local machine:
- **Node.js** (v14 or higher) and npm (bundled with Node.js)
- A package manager like `npm` or `yarn`

---

## 📁 Project Structure

The project is organized into two main directories:
1. **`server/`**: Contains the backend application built with Node.js and Express.
2. **`client/`**: Contains the frontend application built with React and Vite.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-folder>

Install Server Dependencies
cd server
npm install
---

##Create .env File in Server Folder

CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
CLOUDINARY_API_KEY=<your-cloudinary-api-key>
CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>
MONGO_URL="<your-mongodb-connection-string>"
JWT_SECRET="<your-jwt-secret>"

---

## Install Client Dependencies

cd client
npm install

---

##Create .env File in Client Folder

VITE_API=http://localhost:5000


---

🏃 Running the Application
1. Start the Backend Server
cd server
node index.js
2. Start the fronted

cd client
npm run dev
