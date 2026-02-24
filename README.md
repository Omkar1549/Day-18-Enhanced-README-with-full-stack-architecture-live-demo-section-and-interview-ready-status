🚀 JobPro AI: Full-Stack AI Recruitment Engine

📌 Project Overview

JobPro AI is a production-ready, full-stack application designed to automate the modern recruitment workflow. Built over 18 days of intensive development, this project focuses on high-performance backend architecture, intelligent AI parsing, and a seamless user experience.

⚔️ Day 18 Update: Interview War Mode

We have officially moved from "Feature Building" to "Production Hardening." The system is now fully integrated, tested, and ready for a live demo.

🌟 Key Features

AI-Powered Resume Matcher: Uses Google Gemini 2.5 Flash to perform semantic analysis on PDF resumes against Job Descriptions (JDs).

Asynchronous Processing: Leverages FastAPI Background Tasks for non-blocking PDF text extraction and AI scoring.

Dynamic React Dashboard: A modern UI for recruiters to visualize application stats and AI match reports.

Enterprise-Grade Security: Implemented JWT Authentication with Role-Based Access Control (RBAC) to secure Admin and Candidate routes.

Automated Admin Seeder: A professional startup logic that ensures the system is ready to use with a default admin account.

🎬 Live Demo & Screenshots

(Add your video link or screenshots here to impress recruiters!)

Admin Dashboard: Visualizing top talent in seconds.

AI Scoring: Instant feedback on skill gaps.

Swagger Docs: Interactive API exploration at /docs.

🛠️ Tech Stack

Backend: Python, FastAPI, SQLAlchemy ORM, Pydantic.

Frontend: React.js, Tailwind CSS, Lucide Icons.

Database: SQLite (Relational Schema).

AI Integration: Google Gemini API.

Utilities: PyMuPDF (PDF Extraction), Bcrypt (Hashing), Python-JOSE (JWT).

🏗️ System Architecture

.
├── backend/             # FastAPI High-Performance Engine
│   ├── app/
│   │   ├── main.py      # Entry point & CORS Middleware
│   │   ├── models.py    # Relational Database Tables
│   │   ├── schemas.py   # Data Validation Contracts
│   │   ├── auth_utils.py# RBAC & JWT Logic
│   │   └── ai_service.py# Gemini AI Orchestration
│   └── uploads/         # Secure PDF Storage
├── frontend/            # React.js Modern UI
│   └── src/             # Dashboard & Components
└── README.md


🚀 Installation & Setup

Backend Setup:

cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload


Frontend Setup:

cd frontend
npm install
npm start


🏅 Certifications

Google Certified: Maximize Productivity With AI Tools (Authorized by Google via Coursera).

👨‍💻 Developer

Omkar Kandekar
Full Stack Developer | Backend Performance Expert

If you find this project helpful, please consider giving it a ⭐!
