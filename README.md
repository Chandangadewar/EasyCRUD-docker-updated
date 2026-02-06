# 🟦 EasyCRUD Dockerized Application

A full-stack **CRUD application** with modern technologies, fully containerized using **Docker & Docker Compose**.  
The application features a **Spring Boot backend**, **React + Vite frontend**, and **MariaDB database**.

---

## 🚀 Technologies Used
- **Backend:** Spring Boot (Java)  
- **Frontend:** React.js + Vite  
- **Database:** MariaDB  
- **Containerization & Deployment:** Docker & Docker Compose  
- **Environment Management:** .env file for dynamic configuration

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/EasyCRUD-docker-updated.git
cd EasyCRUD-docker-updated
2. Configure environment variables
Open the .env file in the frontend folder

Replace the REACT_APP_BACKEND_URL with your backend IP or localhost if running locally.

3. Build & Start Containers
docker compose up --build
This will start backend, frontend, and MariaDB containers.

4. Access the Application
Frontend: http://localhost:5173 (default Vite port)

Backend API: http://localhost:8080 (default Spring Boot port)

5. Connect to MariaDB
docker exec -it mariadb mysql -u easycrud -p
Username: easycrud

Password: easycrud

🗂️ Project Structure
EasyCRUD-docker-updated/
├── backend/          # Spring Boot backend
├── frontend/         # React + Vite frontend
├── mariadb/          # Database configuration
├── docker-compose.yml
├── .env              # Environment variables
└── README.md
✅ Features
Create, Read, Update, Delete (CRUD) operations for multiple entities

Fully containerized and isolated environments

Easy configuration with .env file

Persistent database using Docker volume
