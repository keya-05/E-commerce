# E-commerce Web Application

A fully functional E-commerce platform that allows users to browse products, manage a shopping cart, and place orders. This project demonstrates a modern full-stack application architecture with a focus on responsive design and user experience.

## 📸 Screenshots

 **Home Page** 
<img width="1920" height="982" alt="Home" src="https://github.com/user-attachments/assets/61785297-e3d4-47b5-aa5d-9b1153ae571c" />
**Shopping Cart** 
 <img width="1920" height="981" alt="Cart" src="https://github.com/user-attachments/assets/5dfc47a6-3f05-472d-985a-ab9bc5373d76" />
 


## 🛠️ Tech Stack

**Frontend:**
*   **React.js:** For building the user interface and component-based architecture.
*   **Redux / Context API:** For state management (Cart handling, User authentication).
*   **CSS / Tailwind CSS / Bootstrap:** For styling and responsive layout.
*   **Axios:** For making HTTP requests to the backend.

**Backend:**
*   **Node.js:** Runtime environment for the server.
*   **Express.js:** Web framework for handling routes and API requests.
*   **MongoDB :** NoSQL database for storing product and user data.
*   **JWT (JSON Web Tokens):** For secure user authentication and authorization.

## 🚀 Setup & Run Guide

Follow these steps to get the project up and running on your local machine.

### Prerequisites
Ensure you have the following installed:
*   [Node.js](https://nodejs.org/) (v14 or higher recommended)
*   [npm](https://www.npmjs.com/) (comes with Node.js)
*   [MongoDB](https://www.mongodb.com/try/download/community) (running locally) **OR** a [MongoDB Atlas](https://www.mongodb.com/atlas) connection string.

### 1. Clone the Repository
```bash
git clone https://github.com/keya-05/E-commerce.git
cd E-commerce

# Enter server directory
cd server

# Install backend dependencies
npm install

# Configure Environment Variables (see .env section below)
cp .env.example .env
# (Manually update .env with your credentials)

# Start the Server
npm start
# OR for development mode (with nodemon)
npm run dev

# Enter client directory
cd ../client

# Install frontend dependencies
npm install

# Start the Client Application
npm start

```

# Setup .env File
```
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```
