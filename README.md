# 🚀 InterviewAI - GenAI Career Companion

InterviewAI is a comprehensive, production-ready full-stack web application designed to help job seekers optimize their resumes, detect skill gaps, and prepare for interviews using the power of Generative AI.

---

## 📌 Project Overview

This application simulates a real-world product that bridges the gap between a candidate's current profile and their target job description. It covers the entire lifecycle from secure authentication to AI-powered content generation and PDF creation.

---

## ✨ Key Features

- 🔐 **Secure Authentication**  
  Robust user management using JWT with custom token blacklisting implementation.

- 📄 **Resume Parsing & AI Analysis**  
  Extracts skills and detects potential skill gaps by comparing user resumes against job descriptions using Google Gemini AI.

- 🤖 **AI Interview Prep**  
  Automatically generates personalized technical and behavioral interview questions based on the job role.

- 🧾 **ATS-Optimized Resume Generation**  
  Uses Puppeteer to dynamically convert AI-refined content into professional, ATS-friendly PDF resumes.

- 📊 **Interactive Dashboard**  
  Manage recent reports, track progress, and rehydrate data seamlessly.

---

## 🛠 Tech Stack

### Frontend
- React.js  
- Vite  
- Axios  
- Tailwind CSS / SCSS  

### Backend
- Node.js  
- Express.js  

### Database
- MongoDB Atlas  

### AI / Processing
- Google Gemini API  
- Puppeteer  

### Validation
- Zod Schema  

---

## 🏗 Architecture Overview

The project follows a modular **4-layer architecture** ensuring scalability and clean code separation:

- 📦 **Presentation Layer** (Frontend UI - React)
- 🔄 **Application Layer** (State Management & Logic)
- ⚙️ **Service Layer** (API handling, business logic)
- 🗄 **Data Layer** (Database interactions - MongoDB)

It also utilizes **context-based state management** for efficient handling of user data and interview reports across the frontend.

# Start backend
cd Backend
npm run dev

# Start frontend
cd Frontend
npx run dev