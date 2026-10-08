# EduCore Requirements Document

## Project Overview

### Project Name

EduCore

### Project Type

School Management System

### Version

v1.0 (MVP)

### Owner

Akinleye Oluwapelumi Micheal

---

# Vision Statement

EduCore is a school management platform designed to help schools manage student information digitally.

The system aims to improve record keeping, reduce administrative workload, and provide a foundation for future academic management features.

---

# Background

Many schools still rely on notebooks, paper files, or spreadsheets for storing student records.

These methods create problems such as:

- Data loss
- Poor organization
- Slow information retrieval
- Human error
- Lack of reporting capabilities

EduCore seeks to provide a simple and affordable solution.

---

# Business Goals

The purpose of EduCore is to:

1. Solve a real-world problem.
2. Build a backend-focused portfolio project.
3. Strengthen practical Node.js skills.
4. Demonstrate software engineering capabilities.
5. Create a solution that can potentially be sold to schools.

---

# Project Scope

## Included in Version 1

### Authentication

Users should be able to:

- Register
- Login
- Access protected resources

---

### Student Management

Administrators should be able to:

- Create students
- View students
- Update students
- Delete students

---

## Excluded from Version 1

The following features will be implemented later:

- Teacher Management
- Attendance
- Result Management
- Fee Management
- Parent Portal
- Notifications
- Report Cards
- Analytics

---

# Target Users

## Administrator

Responsibilities:

- Manage school records
- Manage students

---

## Teacher

Responsibilities:

- View student information

---

## Student

Future implementation.

---

# Functional Requirements

## Authentication Module

### User Registration

The system must allow users to:

- Register account
- Submit credentials
- Store password securely

---

### User Login

The system must allow users to:

- Login
- Receive JWT token
- Access protected routes

---

## Student Module

### Create Student

The system must allow administrators to:

- Add a new student

---

### View Students

The system must allow administrators to:

- Retrieve all students

---

### View Single Student

The system must allow administrators to:

- Retrieve a student by ID

---

### Update Student

The system must allow administrators to:

- Modify student information

---

### Delete Student

The system must allow administrators to:

- Remove student records

---

# Non-Functional Requirements

## Security

- Password hashing using bcrypt
- JWT Authentication
- Input validation

---

## Performance

- Fast API responses
- Efficient database queries

---

## Maintainability

- Clean project structure
- Reusable code
- Proper documentation

---

# Database Design

## User Model

```javascript
{
  (fullName, email, password, role);
}
```

Roles:

```text
ADMIN
TEACHER
```

---

## Student Model

```javascript
{
  (firstName,
    lastName,
    admissionNumber,
    className,
    gender,
    parentName,
    parentPhone,
    dateOfBirth);
}
```

---

# Technology Stack

## Backend

- Node.js
- Express.js

## Database

- MongoDB
- Mongoose

## Authentication

- JWT
- bcrypt

## Deployment

- Render

---

# Development Milestones

## Milestone 1

Project Setup

Tasks:

- Express Setup
- MongoDB Connection
- Environment Configuration

---

## Milestone 2

Authentication Module

Tasks:

- User Model
- Register API
- Login API
- JWT Middleware

---

## Milestone 3

Student Management

Tasks:

- Student Model
- CRUD Operations
- Validation

---

## Milestone 4

API Testing

Tasks:

- Test all routes
- Fix discovered issues

---

## Milestone 5

Deployment

Tasks:

- Deploy API
- Verify production functionality

---

# Success Metrics

EduCore v1 will be considered successful if:

- User registration works
- User login works
- Student CRUD operations work
- API is deployed successfully
- Source code is hosted on GitHub

---

# Future Roadmap

## v2

Teacher Management

## v3

Attendance Module

## v4

Result Management

## v5

Fee Management

## v6

Parent Portal

## v7

School Analytics Dashboard

---

# Personal Project Commitment

Before starting another major project:

- Complete EduCore v1
- Deploy EduCore v1
- Document EduCore v1
- Showcase EduCore on GitHub
