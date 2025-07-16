🔐 OAuth Authentication Service (Personal Project)
A production-grade OAuth2.0 authentication service built with FastAPI, designed to demonstrate secure user authentication, JWT token management, and role-based access control (RBAC).

✨ Why I Built This
To deepen my understanding of OAuth2.0 workflows, stateless authentication with JWT, and scalable API security. This project reflects my ability to implement industry-standard auth systems from scratch.

🛠️ Tech Stack
Backend: Python (FastAPI)

Authentication: OAuth2.0 + JWT, bcrypt for password hashing

Database: SQL (SQLAlchemy ORM)

Tools: Git, Docker (containerization), pytest (testing)

🔥 Key Features
✅ OAuth2.0 Compliance: Supports password grant flow, token refresh, and secure credential handling.
✅ JWT-Based Auth: Stateless token generation/validation with expiry and signature checks.
✅ Role-Based Permissions: Protected routes (e.g., admin-only) using dependency injection.
✅ SQLAlchemy Integration: Efficient CRUD operations for user management.

🚀 Quick Start
Clone and install:
git clone https://github.com/shootea/OAuth.git && cd auth_service  
pip install -r requirements.txt  
Set up .env (copy .env.example):

env
SECRET_KEY="your_random_key"  
DATABASE_URL="sqlite:///./auth.db"  

Run:
uvicorn main:app --reload  
📌 Explore: Interactive docs at http://localhost:8000/docs.

