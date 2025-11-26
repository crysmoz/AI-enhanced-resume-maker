# 🧠 AI-Enhanced Resume Maker (MERN)

![MERN Stack](https://img.shields.io/badge/MERN-Stack-blue)
![Gemini AI](https://img.shields.io/badge/AI-Gemini-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A full-stack MERN application that empowers users to build professional resumes with the intelligence of **Google Gemini AI**. This project leverages a **React (Vite)** frontend, a robust **Node.js/Express** backend, **MongoDB** for persistence, and **ImageKit** for seamless media management.

---

## 🚀 Features

- **📝 Dynamic Resume Builder:** Create and customize professional resumes via an intuitive UI.
- **🤖 AI-Powered Content:** Get smart suggestions for summaries, skills, and experience fields using the **Google Gemini API**.
- **🖼️ Media Management:** Secure image uploads (profile pictures) handling using **ImageKit**.
- **📄 Modern UI/UX:** Fast and responsive client built with **React + Vite**.
- **☁️ Database:** Scalable data storage with **MongoDB**.
- **🔐 Security:** Secure configuration using environment variables.

---

## 🛠️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | React.js, Vite, CSS/Tailwind |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **AI Service** | Google Gemini API |
| **File Storage** | ImageKit.io |

---

## 📂 Folder Structure

```text
resume-builder/
│
├── client/          # Frontend (React + Vite)
├── server/          # Backend (Node.js + Express + MongoDB)
├── .gitignore       # Git ignore rules
└── README.md        # Project documentation
```
🔧 Installation & Setup
⚠️ IMPORTANT: Always run the server first, then the client.

1️⃣ Prerequisites
Ensure you have Node.js installed on your machine. Download Node.js

🗄️ 2️⃣ Setup Backend (SERVER)
Navigate to the server directory:
```text

Bash

cd server
Install dependencies:
```
Bash
```text
npm install
```
Configure Environment Variables: Create a .env file inside the server folder:

Code snippet
```text
MONGO_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_google_gemini_api_key
IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_URL_ENDPOINT=your_url_endpoint
PORT=5000
```
Run the Server:

Bash
```text

npm run server
```
💻 3️⃣ Setup Frontend (CLIENT)
Open a new terminal and navigate to the client directory:

Bash
```text

cd ../client
```
Install dependencies:

Bash
```text

npm install
```
(Optional) Configure Environment Variables: Create a .env file inside the client folder:

Code snippet
```text

VITE_API_URL=http://localhost:5000
Run the Client:
```
Bash
```text

npm run dev
```
🌐 4️⃣ Access the Application
Once both terminals are running, access the application at the links below:

Frontend: http://localhost:5173

Backend: http://localhost:5000

Note: The Backend must be running first for the application to function correctly.

🤝 Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature/YourFeature).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/YourFeature).

Open a Pull Request.

SCREENSHOTS OF PROJECT

<img width="1920" height="1080" alt="Screenshot (653)" src="https://github.com/user-attachments/assets/a208087c-ba2e-42f8-b0fb-5402ac89d659" />
<img width="1920" height="1080" alt="Screenshot (654)" src="https://github.com/user-attachments/assets/4a4e9447-8335-424a-a017-3572d0b3a1d8" />
<img width="1920" height="1080" alt="Screenshot (655)" src="https://github.com/user-attachments/assets/5d269305-1abf-4549-8d43-bd0e74f83db7" />
<img width="1920" height="1080" alt="Screenshot (656)" src="https://github.com/user-attachments/assets/c13694ed-f29b-40eb-9ea2-a1913bc33f96" />
<img width="1920" height="1080" alt="Screenshot (657)" src="https://github.com/user-attachments/assets/e4e2e79a-1864-4fce-a0ae-c62f6e30d814" />
<img width="1920" height="1080" alt="Screenshot (658)" src="https://github.com/user-attachments/assets/705cf935-5d49-4d19-b540-1f92c00aee3d" />
<img width="1920" height="1080" alt="Screenshot (659)" src="https://github.com/user-attachments/assets/1fd4d943-ac8f-486f-843f-2aeea3db3e13" />
<img width="1920" height="1080" alt="Screenshot (660)" src="https://github.com/user-attachments/assets/5d86e5d6-bec0-4b44-849d-64f6b673a3f4" />
<img width="1920" height="1080" alt="Screenshot (661)" src="https://github.com/user-attachments/assets/f846a32e-bab2-4a8b-bd17-fec7d6c6e8de" />
<img width="1920" height="1080" alt="Screenshot (662)" src="https://github.com/user-attachments/assets/03a1b6a5-2a4e-4e8e-9118-e9336357f728" />
<img width="1920" height="1080" alt="Screenshot (663)" src="https://github.com/user-attachments/assets/1b5af1b7-7eec-456f-b029-b8c6d9d7f77a" />
<img width="1920" height="1080" alt="Screenshot (664)" src="https://github.com/user-attachments/assets/5a7e3d8c-3c82-4ce7-a329-557ff48d388f" />
