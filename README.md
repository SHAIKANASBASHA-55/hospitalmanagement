# 🏥 Hospital Management System

The Hospital Management System is a full-stack web application designed to simplify and automate hospital operations such as patient registration, doctor management, appointment scheduling, and secure authentication. It provides a centralized platform for administrators, doctors, and patients to manage hospital data efficiently.

---

## 🚀 Features

- 👨‍⚕️ **Patient Management** – Add, update, and view patient details.  
- 🧑‍⚕️ **Doctor Management** – Maintain doctor profiles and schedules.  
- 📅 **Appointment Booking** – Schedule and manage appointments.  
- 🔐 **User Authentication** – Secure login and registration for patients and doctors.  
- 🏥 **Admin Dashboard** – Monitor all hospital operations in one place.  

---

## 🛠️ Tech Stack

| Layer | Technology |
|--------|-------------|
| **Frontend** | React (Vite), HTML, CSS, JavaScript |
| **Backend** | Spring Boot |
| **Database** | MySQL |
| **Version Control** | Git & GitHub |
| **Containerization** | Docker |

---

## ⚙️ Installation and Setup

1️⃣ Clone the Repository
git clone https://github.com/SHAIKANASBASHA-55/hospitalmanagement.git

2️⃣ Backend Setup
cd hospital-backend
mvn spring-boot:run

3️⃣ Frontend Setup
cd hospital-frontend
npm install
npm run dev

🔗 API Endpoints
Method	Endpoint	Description
POST	/auth/signup	Register a new user
POST	/auth/login	Login and generate JWT token
GET	/patients	Get all patients
GET	/doctors	Get all doctors
POST	/appointments	Book a new appointment

🐳 Docker Setup (Optional)
docker-compose up --build


This will run both backend and frontend services in containers.

👩‍💻 Developed By

SHAIKANASBASHA-55
💡 Built with React, Spring Boot, and MySQL.
