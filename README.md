# 🌍 Travel-Memory – Capture, Relive & Share Your Journeys

**Travel-Memory** is a full-stack travel journal web application built using the **MERN stack**.  
It allows users to record, manage, and revisit their travel experiences by creating digital travel memories enriched with images, locations, and descriptions.

This project demonstrates real-world **full-stack development**, including authentication, RESTful APIs, database design, and responsive UI development.

## ✨ Key Highlights

- 📸 Create beautiful travel memories with images
- 🗺️ Store travel location details
- 🔐 Secure user authentication using JWT
- 📝 Full CRUD functionality for travel memories
- 📱 Responsive and user-friendly UI
- 🌐 REST API-based backend architecture

## 🧠 Application Features

### 👤 User Authentication
- User registration and login
- Secure password handling
- JWT-based authentication
- Protected routes for authorized users only

### 🧳 Travel Memories
- Add new travel memories with:
  - Title
  - Description
  - Location
  - Images
  - Date of travel
- Edit existing memories
- Delete memories
- View all saved memories in a clean UI

### 🖼️ Image Handling
- Upload and display travel images
- Associate images with specific memories

### 📱 Responsive UI
- Works smoothly across desktop, tablet, and mobile devices
- Clean and minimal design for better user experience

## 🛠️ Tech Stack

### Frontend
- **React.js**
- CSS
- Axios (for API calls)

### Backend
- **Node.js**
- **Express.js**
- RESTful APIs

### Database
- **MongoDB**
- Mongoose ODM

### Authentication & Security
- JSON Web Tokens (JWT)
- Environment variables for sensitive data

## 🗂️ Project Structure

Travel-memory/
│
├── client/ # Frontend (React)
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── services/
│ │ └── App.js
│ └── package.json
│
├── server/ # Backend (Node + Express)
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── middleware/
│ ├── config/
│ └── index.js
│
├── .gitignore
└── README.md
