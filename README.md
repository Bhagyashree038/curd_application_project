# 📌 CRUD Application (MERN Stack)

A simple **CRUD (Create, Read, Update, Delete)** application built using the **MERN stack**:  
- **MongoDB** – Database  
- **Express.js** – Backend framework  
- **React.js** – Frontend framework  
- **Node.js** – Server runtime  

This project demonstrates basic CRUD operations with a clean structure for both client and server.

---

## 🚀 Features
- Create new records
- Read and display records
- Update existing records
- Delete records
- RESTful API with Express
- MongoDB integration
- Responsive React frontend

---

## 🛠 Tech Stack
**Frontend:** React, Axios, CSS  
**Backend:** Node.js, Express.js  
**Database:** MongoDB (Compass or Atlas)  
**Version Control:** Git & GitHub  

---

## 📂 Project Structure
```
CRUD_APPLICATION/
├── client/                      # Frontend (React)
│   ├── public/                  # Static files
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   └── manifest.json
│   ├── src/                     # React source code
│   │   ├── adduser/             # Component for adding users
│   │   ├── getuser/             # Component for fetching users
│   │   ├── updateuser/          # Component for updating users
│   │   ├── App.css
│   │   ├── App.js
│   │   ├── index.js
│   │   └── background.avif       # (your background image)
│   ├── .gitignore
│   ├── package.json
│   └── package-lock.json
│
├── server/                      # Backend (Node.js + Express)
│   ├── controller/              # Route controllers
│   ├── model/                   # Database models
│   ├── routes/                  # API routes
│   ├── .env                     # Environment variables (ignored by git)
│   ├── .gitignore
│   ├── index.js                 # Entry point of the server
│   ├── package.json
│   └── package-lock.json
│
├── node_modules/                # Dependencies (ignored by git)
└── .git/                        # Git folder (not pushed to repo)
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Bhagyashree038/crud_application_project.git
cd your-repo-name
```
###2️⃣ Install Dependencies
Install server dependencies:
```bash
cd server
npm install
```
Install client dependencies:
```bash
cd ../client
npm install
```
###3️⃣ Setup MongoDB
Make sure you have MongoDB installed & running locally
Or use MongoDB Atlas cloud database
Create a .env file inside the server/ folder and add:
```ini
MONGO_URI=your_mongodb_connection_string
PORT=5000
```
###4️⃣ Run the Application
Start the backend server:
```bash
cd server
npm start
```
Start the frontend client:
```bash
cd client
npm start
```

App will run on:
Frontend → http://localhost:3000
Backend → http://localhost:5000

###📌 API Endpoints
| Method | Endpoint        | Description     |
| ------ | --------------- | --------------- |
| GET    | /api/items      | Get all items   |
| POST   | /api/items      | Create new item |
| PUT    | /api/items/\:id | Update an item  |
| DELETE | /api/items/\:id | Delete an item  |
