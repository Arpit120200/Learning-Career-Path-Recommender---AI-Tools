# Learning-Career-Path-Recommender & AI-Tools

A web-based application designed to assist users in exploring suitable career paths based on their interests, academic background, and technical skills. This project combines a React frontend with a FastAPI backend and is deployed on Render.

<b>Protoype for the Project</b>: https://colab.research.google.com/drive/1YsRv90BtDMy61iYbO6F21BWeHCyptJ4H?usp=sharing

<b>Access the live application here:</b>
👉 https://cp-frontend-lbv0.onrender.com

📁 <b>Project Structure</b>
project-16/<br>
├── backend/              &nbsp;&nbsp;&nbsp;&nbsp;# FastAPI backend for predictions and API handling<br>
├── frontend/             &nbsp;&nbsp;&nbsp;&nbsp;# React frontend for user interaction<br>
├── .bolt/                &nbsp;&nbsp;&nbsp;&nbsp;# Configuration for Bolt (AI model assistant)<br>
│   ├── config.json<br>
│   └── prompt<br>
└── .DS_Store             &nbsp;&nbsp;&nbsp;&nbsp;# MacOS system file (can be ignored)<br>

<b>Local Setup</b>
<ol>
  <b><li>Clone the Repository</b></li>
  <ul>
     <li>git clone https://github.com/your-username/file-name.git</li>
     <li>cd file-name</li>
  </ul>
  <br>
  <b><li>Start the Backend</b></li>
  Ensure Python 3.8+ is installed.
  <ul>
     <li>cd backend</li>
     <li>pip install -r requirements.txt</li>
     <li>python3 -m uvicorn main:app --reload</li>
  </ul>

  <br>
  <b><li>Start the Frontend</b></li>
  Ensure Node.js (v14 or above) and npm are installed.
  <ul>
     <li>cd frontend</li>
     <li>npm install</li>
     <li>npm run dev</li>
  </ul>

  <br>
  <b><li>Access the App</b></li>
  Once both backend and frontend are running, open:
    📍 <a href="http://localhost:5173">http://localhost:5173</a>
</ol>

📦 <b>Tech Stack</b>
<ul>
  <li>Frontend: React, Vite, TailwindCSS</li>
  <li>Backend: FastAPI, Uvicorn</li>
  <li>Deployment: Render (for frontend), optionally can be extended to deploy backend as well</li>
  <li>Others: JSON-based skill matching logic, AI-driven prompt configuration (via .bolt folder)</li>
</ul>

📌 <b>Notes</b>
<ul>
  <li>The .bolt/ folder is used for prompt and config files to assist with AI-driven logic.</li>
  <li>The .DS_Store file can be removed; it's auto-generated on macOS.</li>
</ul>
