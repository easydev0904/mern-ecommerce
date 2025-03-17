# MERN E-commerce Project

## 📌 Overview
This is a fully functional **E-commerce** web application built using the **MERN (MongoDB, Express, React, Node.js)** stack. It includes product listings, user authentication, and order management.

---

## 🚀 Features
- **User Authentication** (Register/Login with JWT)
- **Product Management** (Add, Edit, Delete products)
- **Order Processing**
- **REST API** with Express & MongoDB
- **Redux Toolkit for State Management**

---

## 🛠️ Tech Stack
- **Frontend:** React, Redux, Axios, React Router
- **Backend:** Node.js, Express, MongoDB, JWT Authentication
- **Database:** MongoDB
- **Package Manager:** npm

---

## 📂 Folder Structure
```
mern-ecommerce/
│── backend/         # Node.js + Express backend
│   ├── models/      # Mongoose models
│   ├── routes/      # API routes
│   ├── server.js    # Main backend server
│
│── frontend/        # React frontend
│   ├── src/
│   │   ├── components/ # UI Components
│   │   ├── reducers/   # Redux reducers
│   │   ├── store.js    # Redux store
│   │   ├── App.js      # Main app component
│   ├── package.json
│
│── .gitignore       # Ignore node_modules & env files
│── README.md        # Project documentation
```

---

## 🚀 Getting Started (Mac OS)
### 1️⃣ Clone the repository
```sh
git clone https://github.com/your-username/mern-ecommerce.git
cd mern-ecommerce
```

### 2️⃣ Install Homebrew (if not installed)
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### 3️⃣ Install Node.js & npm (if not installed)
```sh
brew install node
node -v   # Check Node.js version
npm -v    # Check npm version
```

### 4️⃣ Backend Setup
```sh
cd backend
npm install
npm run dev
```

### 5️⃣ Frontend Setup
```sh
cd frontend
npm install
npm start
```

---

## 🌍 Environment Variables
Create a `.env` file in the `backend/` folder and add:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

## 📜 License
This project is open-source and available under the **MIT License**.

