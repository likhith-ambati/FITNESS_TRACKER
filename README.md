# 🏋️‍♂️ Fitness Tracker

## 📘 Project Documentation

**Project Title:** Fitness Tracker  
**Due Date:** 12/07/2024  
**Completion Date:** 12/07/2024  

---

## 🧾 Project Summary

The **Fitness Tracker** web app helps users monitor their fitness activities, review exercise history, and manage their fitness data efficiently.  
It includes two types of exercises, a search feature for quick navigation, and secure record management.  
User authentication ensures **data privacy and security** through sign-up, sign-in, and sign-out functionality.  

The app is built using the **MERN stack**:  
**MongoDB**, **ExpressJS**, **ReactJS**, and **NodeJS**.

---

## 🌐 Deployment

- **Development Platform:** Render  
- **Deployment Link:** [https://fitnetrackerss--m38e.onrender.com/](https://fitnetrackerss--m38e.onrender.com/)  
- **GitHub Repository:** [https://github.com/Chaitanya071103/capstone](https://github.com/Chaitanya071103/capstone)

---

## ⚙️ Tech Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | React.js |
| **Backend** | Node.js, Express.js, MongoDB Atlas |
| **Database** | MongoDB |
| **Deployment** | Render |
| **Development Tools** | Visual Studio Code, Git, GitHub |

---

## 👨‍💻 Team Members

| Name | Reg. No. | Role |
|------|-----------|------|
| **Chidella Karthikeya** | 22BCE9427 | Backend Developer |
| **Pradeep Reddy** | 22BCE20130 | Backend Developer |
| **A.G. Sai Likhith** | 22BCE9631 | Frontend Developer |
| **K.V. Chaitanya** | 22BCE9853 | Frontend Developer |

---

## 📋 Responsibilities

| Name | Responsibilities |
|------|------------------|
| **Pradeep Reddy** | Database Schema Design, Data Management |
| **Chidella Karthikeya** | Integration, Testing, Deployment |
| **Sai Likhith** | UI Design, React Components, Client-Side Routing |
| **K.V. Chaitanya** | API Development, Middleware Setup, Authentication |

---

## 🎨 Frontend Developer Tasks

- Developed **React.js components** for UI (SignIn, SignUp, Dashboard, Workout History).
- Integrated **API calls** for authentication and data retrieval.
- Built **workout tracking and history display** features.
- Managed state and sessions using **React Context API** and **localStorage**.

---

## 🖥️ Backend Developer Tasks

- Configured **Node.js** server using **Express.js**.
- Developed **API endpoints** for user authentication.
- Integrated **MongoDB** using **Mongoose** for data management.

---

## 💡 Problem Definition

The Fitness Tracker project aims to provide a **centralized platform** for users to efficiently manage and track their fitness progress over time.  
It ensures a **user-friendly interface** for logging, viewing, updating, and deleting workout records.

---

## ✅ Solution Specification

The system provides the following core functionalities:

- User Authentication  
- Workout Data Recording  
- View Workout History  
- Update & Delete Records  
- Generate Workout Reports  
- Responsive Design for All Devices  

---

## 🔤 Variables

| Variable Name | Type | Description |
|----------------|------|-------------|
| `username` | String | Stores username |
| `email` | String | Stores user email |
| `password` | String | Stores password |
| `category` | String | Stores workout category |
| `duration` | Number | Duration of activity |
| `date` | Object | Date of activity |

---

## ⚙️ Functions

| Function Name | Parameters | Description |
|----------------|-------------|--------------|
| `handleRegister` | username, email, password | Handles user registration |
| `handleLogin` | username, password | Handles user login |
| `addRecord` | category, duration | Adds new fitness record |
| `deleteRecord` | recordId | Deletes a fitness record |

---

## 🧩 API Endpoints

### 🔐 User APIs

**Register User**  
`POST /api/auth/signup`  
Registers a new user.

**Login User**  
`POST /api/auth/signin`  
Authenticates user and returns JWT token.

---

### 💪 Fitness APIs

**Record Workout Activity**  
`POST /api/fitness/record`  
Records a new workout activity.

---

## 🧱 Architecture Overview

**Frontend (React.js):**
- Builds UI components and handles routing with React Router.
- Sends HTTP requests to backend using Axios.

**Backend (Express.js):**
- Handles API endpoints and JWT-based authentication.
- Connects to MongoDB using Mongoose.

**Database (MongoDB):**
- Stores user credentials and fitness activity logs.

---

## 📄 License

This project is licensed for educational purposes by the development team.
