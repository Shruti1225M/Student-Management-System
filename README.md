# Student-Management-System

student-management-system/
│
├── frontend/                        # React (Vite)
│   ├── public/
│   │   ├── favicon.ico
│   │   └── logo.png
│   │
│   ├── src/
│   │   ├── assets/
│   │   │   ├── images/
│   │   │   ├── icons/
│   │   │   └── styles/
│   │   │
│   │   ├── components/
│   │   │   ├── common/
│   │   │   │   ├── Button.jsx
│   │   │   │   ├── Input.jsx
│   │   │   │   ├── Modal.jsx
│   │   │   │   ├── Loader.jsx
│   │   │   │   └── Table.jsx
│   │   │   │
│   │   │   ├── layout/
│   │   │   │   ├── Navbar.jsx
│   │   │   │   ├── Sidebar.jsx
│   │   │   │   ├── Footer.jsx
│   │   │   │   └── DashboardLayout.jsx
│   │   │   │
│   │   │   ├── auth/
│   │   │   │   ├── LoginForm.jsx
│   │   │   │   └── RegisterForm.jsx
│   │   │   │
│   │   │   ├── student/
│   │   │   ├── teacher/
│   │   │   ├── course/
│   │   │   ├── attendance/
│   │   │   └── marks/
│   │   │
│   │   ├── pages/
│   │   │   ├── Login.jsx
│   │   │   ├── Register.jsx
│   │   │   ├── Dashboard.jsx
│   │   │   ├── Students.jsx
│   │   │   ├── StudentDetails.jsx
│   │   │   ├── Teachers.jsx
│   │   │   ├── Courses.jsx
│   │   │   ├── Attendance.jsx
│   │   │   ├── Marks.jsx
│   │   │   ├── Profile.jsx
│   │   │   ├── Settings.jsx
│   │   │   └── NotFound.jsx
│   │   │
│   │   ├── routes/
│   │   │   ├── AppRoutes.jsx
│   │   │   ├── PrivateRoute.jsx
│   │   │   └── RoleProtectedRoute.jsx
│   │   │
│   │   ├── services/
│   │   │   ├── api.js
│   │   │   ├── authService.js
│   │   │   ├── studentService.js
│   │   │   ├── teacherService.js
│   │   │   ├── attendanceService.js
│   │   │   ├── marksService.js
│   │   │   └── courseService.js
│   │   │
│   │   ├── context/
│   │   │   ├── AuthContext.jsx
│   │   │   └── ThemeContext.jsx
│   │   │
│   │   ├── hooks/
│   │   │   ├── useAuth.js
│   │   │   └── useFetch.js
│   │   │
│   │   ├── utils/
│   │   │   ├── constants.js
│   │   │   ├── validators.js
│   │   │   ├── helpers.js
│   │   │   └── storage.js
│   │   │
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   │
│   ├── package.json
│   ├── vite.config.js
│   ├── .env
│   └── Dockerfile
│
│
├── backend/                         # Node.js + Express
│   ├── config/
│   │   ├── db.js
│   │   └── jwt.js
│   │
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── studentController.js
│   │   ├── teacherController.js
│   │   ├── courseController.js
│   │   ├── attendanceController.js
│   │   └── marksController.js
│   │
│   ├── middleware/
│   │   ├── authMiddleware.js
│   │   ├── roleMiddleware.js
│   │   ├── errorMiddleware.js
│   │   └── validateMiddleware.js
│   │
│   ├── models/
│   │   ├── Student.js
│   │   ├── Teacher.js
│   │   ├── Course.js
│   │   ├── Attendance.js
│   │   └── Marks.js
│   │
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── studentRoutes.js
│   │   ├── teacherRoutes.js
│   │   ├── courseRoutes.js
│   │   ├── attendanceRoutes.js
│   │   └── marksRoutes.js
│   │
│   ├── services/
│   │   ├── authService.js
│   │   ├── studentService.js
│   │   └── teacherService.js
│   │
│   ├── utils/
│   │   ├── generateToken.js
│   │   ├── password.js
│   │   └── logger.js
│   │
│   ├── database/
│   │   ├── schema.sql
│   │   ├── seed.sql
│   │   └── migrations/
│   │
│   ├── uploads/
│   │
│   ├── app.js
│   ├── server.js
│   ├── package.json
│   ├── .env
│   └── Dockerfile
│
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
├── .gitignore
├── docker-compose.yml
├── README.md
├── LICENSE
└── package.json (optional if using workspaces)
