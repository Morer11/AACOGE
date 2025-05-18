# AACOGE - Full Stack Web App

This is a full stack web application that generates complete, downloadable website source code from user descriptions, powered by AI.
Created by AADev you can contact for any query to my gmail:aliyuaadam1111@gmail.com
---

## Features

- AI-powered website source code generation based on your descriptions (using OpenAI API)
- Language/framework selection (Vanilla HTML/CSS/JS, React, Vue)
- User accounts with authentication (JWT)
- Create, save, and manage projects
- Live preview of generated websites
- Download generated source code as files
- Admin panel (stub for user and template management)
- Modern UI built with React and Tailwind CSS
- Backend API built with Node.js, Express, MongoDB
- Security and code optimization ready to be extended
- Designed for future collaboration, SEO, version control, and deployment features

---

## Tech Stack

- **Backend:**
  - Node.js + Express
  - MongoDB via Mongoose
  - JWT-based Authentication
  - OpenAI API integration for AI code generation

- **Frontend:**
  - React with React Router
  - Tailwind CSS for styling
  - Single Page Application (SPA)

---

## Setup Instructions

### 1. Clone the repository (or copy files)

### 2. Backend Setup

2. Backend Setup 43 44- Navigate to `backend` folder: 45 ```bash 46 cd backend

Create a .env file based on .env.example and fill in your credentials:PORT=4000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key


bash

RunCopy code

1npm run dev

Backend will run on http://localhost:4000

Usage:

Register a new user or login.
Create a new project by providing a title and description of your website.

.Choose your preferred language/framework.
.Click Generate Website to get AI-generated complete website source code.
.Preview your website live in the app.
.Download the generated source code for offline use or deployment.
.Explore and manage your projects from your dashboard.
.Admin panel is available for site management (currently under development).

Notes

.You must have an OpenAI API key to enable AI code generation.
.MongoDB must be accessible by the backend.
.The app uses JWT tokens for secure authentication.
.This is a foundation for a sophisticated AI website builder.
