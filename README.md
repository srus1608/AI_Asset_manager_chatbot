## 💼 AI Asset Management System
AI Asset Management System is a comprehensive platform designed to manage and track digital and physical assets efficiently using AI-driven insights. 
The system includes a robust backend, user-friendly frontend, secure environment setup, and Bluetally integration for enterprise-level asset management.

## 🌟 Features
🔑 User authentication and secure access.
📦 Asset inventory management with AI-based categorization.
📊 Real-time tracking and reporting of assets.
🔔 Notification and alert system for asset updates.
🗄️ Database integration with alembic migrations for schema management.
🔗 Seamless **Bluetally API integration** for secure and real-time asset storage, updates, and lifecycle management.

## 🛠️ Technologies Used
🐍 Python
⚙️ FastAPI (likely backend)
💻 React.js or similar (frontend)
🗃️ PostgreSQL (assumed DB
🔐 .env for environment configurations
🔄 Alembic for DB migrations ☁️
**Bluetally for SaaS-based asset management**.

## 📂 Folder Structure
📁 `backend/` — Backend APIs and business logic.
📁 `frontend/` — Frontend UI for user interaction.
📁 `alembic/` — Database migrations and version control.
📄 `.env` — Environment variables for secure config.
📄 `alembic.ini` — Alembic configuration file.
📄 `create_table.py` — Script to create initial database tables.
📄 `generate_secret_key.py` — Script to generate app secret key.
📄 `main.py` — Main application entry point.
📄 `pyproject.toml` — Project dependencies and configuration.

##  ⚙️ Setup Instructions
1. ⬇️ **Clone the repository**.
2. 📦 **Install backend dependencies** using `pip install -r requirements.txt` (if inside backend folder).
3. 📦 **Install frontend dependencies** (assuming React.js) using `npm install`.
4. 🔐 **Configure `.env` file** with DB credentials, Bluetally API keys, and secret keys.
5. 🗄️ **Run Alembic migrations** using `alembic upgrade head` to set up the database.
6. ▶️ **Run backend server**: `python main.py`.
7. ▶️ **Run frontend server** (assuming React): `npm start`.

## 🚀 Future Improvements
🤖 Add AI-powered predictive analytics for asset usage and maintenance.
📱 Mobile app integration for on-the-go asset management.
🔗 API integrations with third-party asset tracking tools.
🛡️ Enhanced security with OAuth2 or JWT authentication.

## 👨‍💻 Author
Developed by: srushti Talwekar
Contact: srushtirt1608@gmail.com

⭐ If you like this project, give it a star!
