# JobTrack — Job Application Tracker

JobTrack is a full-stack job application management platform that helps users track job applications, companies, interview stages, and application status from a centralized dashboard.

## 🚀 Features

* User registration and login
* JWT-based authentication
* Protected routes
* Create job applications
* Update job applications
* Delete job applications
* Track application status
* Search and filter applications
* Application statistics
* Responsive React dashboard
* RESTful APIs
* PostgreSQL database

## 🛠️ Tech Stack

### Frontend

* React.js
* JavaScript
* HTML
* CSS
* Vite

### Backend

* Node.js
* Express.js
* REST API
* JWT
* bcrypt

### Database

* PostgreSQL

### Tools

* Git
* GitHub
* Postman
* VS Code

## 📂 Project Structure

```text
jobtrack/
├── frontend/
├── backend/
├── database/
├── screenshots/
├── .gitignore
└── README.md
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/jobtrack.git
cd jobtrack
```

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file:

```env
PORT=5000
DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
```

Start the backend:

```bash
npm run dev
```

### 3. Setup Frontend

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

## 🔐 Authentication

JobTrack uses JWT-based authentication.

```text
User
 ↓
Login
 ↓
Server validates credentials
 ↓
JWT generated
 ↓
Protected API requests
 ↓
Authenticated User
```

## 📊 Application Workflow

```text
Register/Login
      ↓
Dashboard
      ↓
Add Job Application
      ↓
Track Status
      ↓
OA / Interview
      ↓
Selected / Rejected
```

## 🔌 API Endpoints

### Authentication

| Method | Endpoint             | Description      |
| ------ | -------------------- | ---------------- |
| POST   | `/api/auth/register` | Register user    |
| POST   | `/api/auth/login`    | Login user       |
| GET    | `/api/auth/me`       | Get current user |

### Jobs

| Method | Endpoint        | Description     |
| ------ | --------------- | --------------- |
| GET    | `/api/jobs`     | Get user's jobs |
| POST   | `/api/jobs`     | Create job      |
| GET    | `/api/jobs/:id` | Get job         |
| PUT    | `/api/jobs/:id` | Update job      |
| DELETE | `/api/jobs/:id` | Delete job      |

## 🗄️ Database

The application uses PostgreSQL to store:

* Users
* Job applications
* Companies
* Application status
* Job roles
* Application dates

## 📸 Screenshots

### Login

![Login](screenshots/login.png)

### Dashboard

![Dashboard](screenshots/dashboard.png)

### Job Applications

![Jobs](screenshots/jobs.png)

## 🔮 Future Improvements

* Email reminders for interviews
* Application deadline notifications
* Resume management
* Analytics and charts
* Job description parser
* Browser extension for saving job applications

## 📌 Project Status

**Ongoing**

The core authentication, job management, REST API, PostgreSQL integration, and dashboard functionality are being developed incrementally.

## 👨‍💻 Author

Rohit Dhakad

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourusername
