<h1 align="center">🩺 Doctor-Patient Appointment Booking System 🩺</h1>

<p align="center">
  <img src="https://art.pixilart.com/486745d4bb1ef18.gif" width="20" height="20">
</p>

<p align="center">
A full-stack web application for scheduling appointments between doctors and patients. Built with a modern tech stack—Node.js for backend services and a frontend framework like React—the platform features secure login, role-based access control, and calendar syncing via the Google Calendar API. The system includes easy-to-use interfaces for users to register, book appointments, and manage schedules. While visual design is kept simple, the app emphasizes clean architecture, secure handling of data, and scalable features like notifications and doctor search.
</p>

---

## 🚀 Technologies Used

### Frontend
<p align="center">
  <img src="https://img.shields.io/badge/react-%23323330.svg?style=for-the-badge&logo=react&logoColor=%23F7DF1E">
  <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white">
</p>

### Backend
<p align="center">
  <img src="https://img.shields.io/badge/expressjs-%777BB4.svg?style=for-the-badge&logo=express.js&logoColor=white">
  <img src="https://img.shields.io/badge/mongoose-%2300f.svg?style=for-the-badge&logo=mongoose&logoColor=white">
</p>

### Tools & Services
<p align="center">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white">
  <img src="https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white">
</p>

---

## ✨ Core Features

### Backend
1. RESTful APIs developed with Node.js and Express.
2. Handles user registration, authentication, and appointment endpoints.
3. Supports MongoDB or PostgreSQL for data storage.
4. Integrates Google Calendar API for syncing appointment events.

### Frontend
1. Built with a frontend library (e.g., React, Angular, or Vue).
2. Interfaces for doctors and patients to register, sign in, and interact.
3. Appointment booking form that integrates with calendar events.
4. Doctor dashboard to manage bookings with real-time updates.

### Authentication
1. Secured using JWT tokens or session-based login.
2. Passwords are encrypted before storing.
3. Only logged-in users can access protected routes.

### Authorization
1. Role-specific access for patients, doctors, and admins.
2. Data and route access controlled based on assigned roles.
3. Doctors can manage appointments; patients can only view or edit their own.

### Optional Add-Ons
1. Email or push notifications for upcoming appointments.
2. Rescheduling and cancellation support for users.
3. Doctor filtering by specialty, location, and availability.

---

## 📋 Evaluation Focus

1. Efficient and modular backend with proper REST principles.
2. Secure login implementation using JWT/session.
3. Optimized database schema and queries.
4. Google Calendar integration functionality.
5. Role-based access implemented correctly.
6. Good input validation and error handling.
7. Added extras like notifications or search (if built).
8. Clean code that follows good development practices.
9. Simplicity in design but richness in functionality.

---

## 📦 Project Structure Overview

### Tech Stack
- **Backend:** Node.js + Express
- **Frontend:** Any modern JS framework (React preferred)
- **Database:** MongoDB or PostgreSQL
- **External APIs:** Google Calendar API

### Functional Modules
1. **API Layer:** Handles user login/signup, appointments, and calendar sync.
2. **Database Models:** Store users, roles, appointments, and profiles.
3. **Frontend UI:** Interfaces for different user roles and workflows.
4. **Auth Middleware:** Verifies and authorizes users via token/session.

---

## 🛠 Getting Started

1. Clone the repo:  
   ```bash
   https://github.com/Divyanshu-500/patient-doctor-appointment.git
2. Set up the backend API using Express and Mongoose (provide instructions if necessary).
3. Navigate to the project directory.
4. Run npm install to install the required dependencies.
5. Run npm start to start the development server.
