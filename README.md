# 🧠 AI-Enhanced Resume Maker (MERN)

A full-stack MERN application that helps users build professional resumes with the help of AI.  
This project includes a **React (Vite) client**, **Node.js + Express server**, **MongoDB**, **Google Gemini AI**, and **ImageKit** for image uploads.

---

## 🚀 Features
- 📝 Create & customize resumes
- 🤖 AI-powered content suggestions (Gemini API)
- 🖼️ Image uploads using ImageKit
- 📄 Modern UI built with React + Vite
- ☁️ MongoDB for data storage
- 🔐 Secure environment variable configuration

---
## 📂 Folder Structure
resume-builder/
│── client/ # Frontend (React + Vite)
│── server/ # Backend (Node.js + Express + MongoDB)
│── .gitignore
│── .env.example
│── README.md


# 🔧 How to Setup & Run the Project

> ⚠️ **IMPORTANT: Always run the server first, then the client.**

---

## 🖥️ 1️⃣ Install Node.js (Skip if already installed)

Download from:  
https://nodejs.org/en/download/

---

# 🗄️ 2️⃣ Setup Backend (SERVER)

### 1. Navigate to the server folder
```bash
cd server
2. Install backend dependencies
bash
Copy code
npm install

3. Create .env file inside the server folder
MONGO_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_google_gemini_api_key
IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_URL_ENDPOINT=your_url_endpoint
PORT=5000

4. Run the backend server
npm run server


Backend runs at:
👉 http://localhost:5000

5000

💻 3️⃣ Setup Frontend (CLIENT)
1. Navigate to client folder
cd ../client


2. Install frontend dependencies
npm install

3. (Optional) Create .env file inside client
VITE_API_URL=http://localhost:5000

4. Run the frontend
npm run dev


Frontend runs at:
👉 http://localhost:5173

🌐 4️⃣ Access the Application

Frontend: http://localhost:5173

Backend: http://localhost:5000

(Backend must be running first.)
