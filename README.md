# Job Portal Application 🌟

The **Job Portal Application** is a MERN-based full-stack web application designed to connect students and recruiters, providing a platform for job search, application submission, and efficient management of user and company profiles.

[![React](https://img.shields.io/badge/React-18.2.0-blue.svg)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-20.5.1-green.svg)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-7.0.2-brightgreen.svg)](https://www.mongodb.com/)
[![Express](https://img.shields.io/badge/Express-4.18.2-lightgrey.svg)](https://expressjs.com/)

---

## ✨ Features

- **Role-Specific Access**: Distinct roles for students and recruiters, offering tailored user experiences.
- **Job Search and Applications**: Allows users to search and apply for jobs with ease.
- **Company and Profile Management**: Enables recruiters to create and manage company profiles and job listings.
- **Secure Authentication**: Implements JWT-based authentication for safe and reliable user sessions.
- **Scalability and Security**: Designed to support role-based permissions and efficient data handling.

---

## 🛠️ Tech Stack

### Core Technology
- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Database**: MongoDB (with Mongoose for schema modeling)

### Key Libraries and Tools
- **Authentication**: JSON Web Tokens (JWT)
- **State Management**: Redux Toolkit
- **Styling**: Tailwind CSS
- **API Testing**: Postman

---

## 🚀 Getting Started

### Prerequisites

To run this project, you will need:
- Node.js (v16 or later)
- npm or yarn for dependency management
- MongoDB server running locally or in the cloud

### Setup Guide

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/siddharthdhodi05/Job-Portal-Application.git
   cd Job-Portal-Application  
   ```
---

## 🔧 Environment Setup

### Environment Variables  
Create a `.env` file in the `backend` directory and add the following:  

```env
MONGO_URI= Your mongoDB Url
PORT=8000
CLOUD_NAME= Cloudinary name
API_KEY= Cloudinary Api key
API_SECRET= Cloudinary Api secret
SECRET_KEY= for jwt autentication  
```
---

# Run the Application

## Start the Backend Server:
Navigate to the backend directory and run:

```bash
cd backend
npm run dev
```

## Start the Frontend Server:
Navigate to the forntend directory and run:
```bash
cd frontend
npm run dev
```

