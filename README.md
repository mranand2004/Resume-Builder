# 🚀 AI-Powered Resume Builder (MERN Stack)

An **AI-powered Resume Builder web application** that allows users to create, customize, preview, and download professional resumes using multiple modern templates.  
Built using the **MERN stack**, with **AI-assisted content generation**, secure authentication, and a clean, responsive UI.

---

## 📌 Features

### 🔐 Authentication
- User Registration & Login
- JWT-based authentication
- Protected routes using middleware

### 📝 Resume Builder
- Personal Information
- Professional Summary
- Skills
- Education
- Experience
- Projects
- Live Resume Preview

### 🎨 Templates
- Classic Template
- Minimal Template
- Modern Template
- Minimal Image Template
- Custom color selection

### 🤖 AI Integration
- AI-generated professional summaries
- AI-enhanced resume content
- Improves wording and structure

### 📄 Export & Preview
- Real-time resume preview
- Printable resume layout
- Clean and professional formatting

### ☁️ Media & Storage
- Image upload support (profile photo)
- ImageKit integration
- Multer for file handling

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- Redux Toolkit
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication

### AI & Utilities
- OpenAI / AI API integration
- ImageKit
- Multer

---

## 📁 Project Structure

resume-builder/
│
├── client/ # Frontend (React)
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── assets/
│ │ ├── app/ # Redux store & slices
│ │ └── configs/
│ └── vite.config.js
│
├── server/ # Backend (Node + Express)
│ ├── configs/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middlewares/
│ └── server.js
│
├── How_To_Run_Project.pdf
└── README.md


---

## ⚙️ Environment Variables

### 📍 Client (`client/.env`)
```env
VITE_API_BASE_URL=http://localhost:5000

📍 Server (server/.env)
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
AI_API_KEY=your_ai_api_key

IMAGEKIT_PUBLIC_KEY=your_key
IMAGEKIT_PRIVATE_KEY=your_key
IMAGEKIT_URL_ENDPOINT=your_url

▶️ How to Run the Project Locally
1️⃣ Clone the Repository
git clone https://github.com/your-username/resume-builder.git
cd resume-builder

2️⃣ Start Backend
cd server
npm install
npm run dev


Server will run at:

http://localhost:5000

3️⃣ Start Frontend
cd client
npm install
npm run dev


Frontend will run at:

http://localhost:5173

🔐 Authentication Flow

User registers or logs in

JWT token is generated

Token is stored on client

Protected APIs use auth middleware

User can create & manage resumes securely

🤖 AI Resume Generation Flow

User provides basic input

AI API generates professional content

Content is editable

Stored in MongoDB

Rendered in real-time resume preview

🚀 Deployment (Recommended)
Frontend

Vercel / Netlify

Backend

Render / Railway / Cyclic

Database

MongoDB Atlas

🧠 Future Enhancements

PDF download support

Multiple resume versions per user

Resume sharing via link

Cover letter generator

Admin dashboard

👨‍💻 Author

Anand Dwivedi
🎓 B.E. Computer Science
💻 MERN Stack Developer
🏆 Hackathon Finalist
📍 Chandigarh University

⭐ Show Your Support

If you like this project:

⭐ Star this repository

🍴 Fork it

📢 Share it
