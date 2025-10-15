🏥 Hospital Management System

A full-stack web application built to streamline hospital operations including patient registration, doctor management, appointment scheduling, and authentication.
The system features a React (Vite) frontend and a Spring Boot backend connected to a MySQL database.

🚀 Features
👨‍⚕️ Patient Module

Patient registration and login

View and update profile

Book appointments with doctors

🧑‍⚕️ Doctor Module

Doctor registration and authentication

View scheduled appointments

Update availability status

🏢 Admin Module

Manage patients and doctors

Monitor hospital activities

🔐 Authentication

Secure login/signup using JWT tokens

Role-based access control (Admin / Doctor / Patient)

🏗️ Tech Stack
Layer	Technology
Frontend	React.js (Vite), HTML5, CSS3, Tailwind / Bootstrap
Backend	Spring Boot (Java)
Database	MySQL
API Testing	Postman
Deployment	Docker, GitHub, (Optional: Render / AWS / Azure)
📂 Project Structure
hospital-management/
│
├── hospital-frontend/     # React Vite frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
│   └── package.json
│
├── hospital-backend/      # Spring Boot backend
│   ├── src/main/java/com/hospital/...
│   ├── pom.xml
│   └── application.properties
│
└── README.md

⚙️ Installation & Setup
🔹 Prerequisites

Ensure you have the following installed:

Node.js

Java JDK 17+

MySQL

Maven

Git

🔹 Backend Setup
# Clone backend repository
git clone https://github.com/yourusername/hospital-backend.git
cd hospital-backend

# Configure MySQL in application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/hospitaldb
spring.datasource.username=root
spring.datasource.password=yourpassword

# Run backend
mvn spring-boot:run


✅ The backend will start on http://localhost:8081

🔹 Frontend Setup
# Clone frontend repository
git clone https://github.com/yourusername/hospital-frontend.git
cd hospital-frontend

# Install dependencies
npm install

# Start the app
npm run dev


✅ The frontend will start on http://localhost:5173

🔗 API Endpoints
Method	Endpoint	Description
POST	/auth/signup	Register new user
POST	/auth/login	User login
GET	/patients	Fetch all patients
GET	/doctors	Fetch all doctors
POST	/appointments	Book appointment
🐳 Docker Setup (Optional)
# Build and start containers
docker-compose up --build

# Stop containers
docker-compose down

📸 Screenshots (Optional)

Add screenshots here (Login Page, Dashboard, Appointments, etc.)

🧪 Testing

You can test backend APIs using Postman or cURL.

Example:

curl -X POST http://localhost:8081/auth/login \
-H "Content-Type: application/json" \
-d '{"username":"admin","password":"admin123"}'
