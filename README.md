# 🎓 Student Management System

A full-stack Student Management System built using **React.js, Node.js, Express.js, PostgreSQL**, JWT Authentication, Role-Based Access Control (RBAC), and Docker.

---

# 📌 Features

- 🔐 JWT Authentication
- 👨‍🎓 Student Management
- 👨‍🏫 Teacher Management
- 📚 Course Management
- 📝 Attendance Management
- 📊 Marks Management
- 📈 Dashboard & Analytics
- 👥 Role-Based Access (Admin, Teacher, Student)
- 📂 File Upload Support
- 🐳 Docker Deployment
- 📱 Responsive UI

---

# 🛠 Tech Stack

## Frontend

- React.js
- React Router
- Axios
- Context API
- Tailwind CSS / Bootstrap

## Backend

- Node.js
- Express.js
- JWT Authentication
- bcrypt
- Multer

## Database

- PostgreSQL

## DevOps

- Docker
- Docker Compose
- Git & GitHub

---

# 📂 Project Structure

```
Student-Management-System/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── layouts/
│   │   ├── pages/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   ├── package.json
│   └── Dockerfile
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── utils/
│   ├── database/
│   ├── uploads/
│   ├── app.js
│   ├── server.js
│   ├── package.json
│   ├── .env
│   └── Dockerfile
│
├── database/
│   ├── ER_Diagram.png
│   ├── schema.sql
│   └── sample_data.sql
│
├── docs/
│   ├── API_Documentation.md
│   ├── Project_Report.pdf
│   ├── Screenshots/
│   └── Architecture.png
│
├── docker-compose.yml
├── .gitignore
├── LICENSE
└── README.md
```

---

# 🗄 Database Design

## Main Tables

- Users
- Students
- Teachers
- Courses
- Enrollments
- Attendance
- Marks

---

# 👤 User Roles

## Admin

- Manage Students
- Manage Teachers
- Manage Courses
- Assign Teachers
- View Reports

### Teacher

- Manage Attendance
- Upload Marks
- View Students
- Update Profile

### Student

- View Profile
- View Attendance
- View Marks
- View Courses

---

# 🔐 Authentication Flow

```
Login
   │
   ▼
Verify Credentials
   │
   ▼
Generate JWT Token
   │
   ▼
Store Token
   │
   ▼
Protected Routes
```

---

# 📡 REST API

## Authentication

```
POST   /api/auth/register
POST   /api/auth/login
GET    /api/auth/profile
```

## Students

```
GET    /api/students
GET    /api/students/:id
POST   /api/students
PUT    /api/students/:id
DELETE /api/students/:id
```

## Teachers

```
GET
POST
PUT
DELETE
```

## Courses

```
GET
POST
PUT
DELETE
```

## Attendance

```
GET
POST
PUT
DELETE
```

## Marks

```
GET
POST
PUT
DELETE
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Student-Management-System.git
```

## Frontend

```bash
cd frontend
npm install
npm run dev
```

## Backend

```bash
cd backend
npm install
npm start
```

---

# 🐳 Docker

```bash
docker-compose up --build
```

---

# 📷 Screenshots

```
docs/
└── Screenshots/
```

- Login
- Dashboard
- Student Module
- Teacher Module
- Attendance
- Marks

---

# 📜 Future Improvements

- Email Notifications
- QR Attendance
- Parent Portal
- Timetable Module
- Fees Management
- AI Analytics
- Mobile Application

---

# 👨‍💻 Author

**Shruti Meshram**

B.Tech Computer Science & Technology

IIEST Shibpur

2026 Graduate

---

# 📄 License

This project is licensed under the MIT License.
