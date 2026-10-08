# EduCore Backend

EduCore is a School Management System API built with Node.js, Express, and MongoDB.

The goal of EduCore is to help schools digitize their administrative operations by managing students, teachers, attendance, academic records, and other school-related activities through a centralized platform.

---

## Project Status

🚧 Currently In Development

Version: v1.0 (MVP)

---

## Features

### Authentication

- User Registration
- User Login
- Password Hashing
- JWT Authentication
- Protected Routes

### Student Management

- Create Student
- View Students
- View Student Details
- Update Student Information
- Delete Student

---

## Future Features

### Teacher Management

- Create Teacher
- Update Teacher
- View Teachers

### Attendance Management

- Mark Attendance
- View Attendance Reports

### Result Management

- Record Student Results
- Generate Academic Reports

### Fee Management

- School Fee Tracking
- Payment History

---

## Tech Stack

### Backend

- Node.js
- Express.js

### Database

- MongoDB
- Mongoose

### Authentication & Security

- JWT
- bcrypt

### Development Tools

- Git
- GitHub
- Postman
- VS Code

---

## Project Structure

```text
src/
│
├── config/
├── controllers/
├── middleware/
├── models/
├── routes/
├── services/
├── utils/
│
├── app.js
└── server.js
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/educore-backend.git
```

### Navigate Into Project

```bash
cd educore-backend
```

### Install Dependencies

```bash
npm install
```

### Create Environment File

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key
```

### Run Development Server

```bash
npm run dev
```

---

## API Endpoints

### Authentication

```http
POST /api/auth/register

POST /api/auth/login
```

### Students

```http
POST /api/students

GET /api/students

GET /api/students/:id

PUT /api/students/:id

DELETE /api/students/:id
```

---

## Learning Objectives

This project is being built to:

- Strengthen backend engineering skills
- Learn REST API development
- Learn Authentication and Authorization
- Gain experience with MongoDB
- Build a portfolio-ready project

---

## Author

Built by Akinleye Oluwapelumi Micheal

Backend Developer | Node.js Enthusiast

---

## License

MIT License
