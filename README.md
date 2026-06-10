<div align="center">

# 🎓 Online Course Registration System

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=7C3AED&center=true&vCenter=true&width=600&lines=Simplify+Course+Enrollment+Online;Student+%26+Admin+Portal;Built+with+HTML+%7C+CSS+%7C+JS+%7C+Node.js" alt="Typing SVG" />

<br/>

![Project Banner](https://img.shields.io/badge/-%F0%9F%8E%93%20Online%20Course%20Registration-7c3aed?style=for-the-badge&labelColor=1a0533)

<br/>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

<br/>

[![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/online-course-registration-system?style=flat-square&color=7c3aed)](https://github.com/yourusername/online-course-registration-system)
[![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/online-course-registration-system?style=flat-square&color=7c3aed)](https://github.com/yourusername/online-course-registration-system/commits)
[![License](https://img.shields.io/badge/License-Educational-green?style=flat-square)](LICENSE)

<br/>

> *A web-based system that eliminates manual paperwork, reduces enrollment errors, and centralizes course management — for students and administrators.*

<br/>

[🚀 Live Demo](#) · [📖 Documentation](#) · [🐛 Report Bug](https://github.com/yourusername/online-course-registration-system/issues) · [💡 Request Feature](https://github.com/yourusername/online-course-registration-system/issues)

</div>

---

## 📸 Screenshots

<div align="center">

| Student Dashboard | Course Listing |
|:-----------------:|:--------------:|
| ![Student Dashboard](./screenshots/student-dashboard.png) | ![Course Listing](./screenshots/course-listing.png) |

| Admin Panel | Registration Form |
|:-----------:|:-----------------:|
| ![Admin Panel](./screenshots/admin-panel.png) | ![Registration](./screenshots/registration.png) |

</div>

> 📁 Add screenshots to a `/screenshots` folder in your repository to display them here.

---

## 📌 Problem Statement

Manual course registration is **slow, error-prone, and fragmented.**

- 🔴 Students struggle to track available courses and enrollment status
- 🔴 Administrators spend hours managing spreadsheets and paperwork
- 🔴 No centralized system leads to data inconsistency and confusion

**This system solves all of that.**

---

## 🎯 Objectives

| # | Goal |
|---|------|
| 1 | Allow students to register for courses online — anytime, anywhere |
| 2 | Enable administrators to manage courses and users from a single dashboard |
| 3 | Eliminate paperwork and manual enrollment effort |
| 4 | Improve data accuracy and system accessibility |

---

## ✨ Features

### 👨‍🎓 Student Module

| Feature | Description |
|---------|-------------|
| 🔐 Authentication | Secure user registration and login |
| 📚 Browse Courses | View all available courses with details |
| ➕ Enroll | Register for desired courses instantly |
| ➖ Unenroll | Drop courses with a single click |
| 📋 My Courses | View all currently enrolled courses |

### 🛠️ Admin Module

| Feature | Description |
|---------|-------------|
| 🔑 Admin Login | Secure admin authentication |
| ➕ Add Course | Create and publish new courses |
| ✏️ Update Course | Edit course details anytime |
| 🗑️ Delete Course | Remove outdated or cancelled courses |
| 👥 View Students | See all registered students |
| 📊 Manage Enrollments | Monitor and control all course enrollments |

### 🌐 General Features

- ✅ Simple and intuitive UI
- ✅ Secure authentication system
- ✅ Fully responsive design (mobile + desktop)
- ✅ Scalable architecture

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Frontend** | HTML5, CSS3, JavaScript | UI & interactivity |
| **Backend** | Node.js | Server-side logic & REST API |
| **Database** | MySQL / MongoDB | Data storage |
| **Version Control** | Git & GitHub | Source management |
| **IDE** | VS Code | Development environment |

</div>

---

## 📁 Project Structure

```
online-course-registration/
│
├── 📂 frontend/
│   ├── index.html          # Landing / Home page
│   ├── login.html          # Login page
│   ├── register.html       # Student registration page
│   ├── style.css           # Global stylesheet
│   └── script.js           # Client-side JavaScript
│
├── 📂 backend/
│   ├── server.js           # Express server entry point
│   └── routes/             # API route handlers
│       ├── auth.js         # Authentication routes
│       ├── courses.js      # Course management routes
│       └── students.js     # Student management routes
│
├── 📂 database/
│   └── schema.sql          # Database schema & tables
│
└── README.md
```

---

## ⚙️ How It Works

```
┌─────────────────────────────────────────────────────────┐
│                   STUDENT FLOW                          │
│                                                         │
│  Register ──► Login ──► Browse Courses ──► Enroll       │
│                              │                          │
│                    View My Enrollments                  │
└─────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────┐
│                    ADMIN FLOW                           │
│                                                         │
│  Login ──► Dashboard ──► Add / Edit / Delete Courses    │
│                │                                        │
│         View Students & Manage Enrollments              │
└─────────────────────────────────────────────────────────┘
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) v18+
- [MySQL](https://www.mysql.com/) or [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)

### Installation

**Step 1 — Clone the repository**

```bash
git clone https://github.com/yourusername/online-course-registration-system.git
cd online-course-registration-system
```

**Step 2 — Set up the database**

```bash
# For MySQL: import the schema
mysql -u root -p < database/schema.sql
```

**Step 3 — Configure environment variables**

Create a `.env` file inside the `/backend` folder:

```env
PORT=3000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=course_registration
```

**Step 4 — Install dependencies and start the server**

```bash
cd backend
npm install
npm start
```

**Step 5 — Open the app**

```
Open frontend/index.html in your browser
         — or —
Visit http://localhost:3000
```

> ⚠️ Never commit your `.env` file. Add it to `.gitignore`.

---

## 📊 Outcomes

<div align="center">

| Before | After |
|:------:|:-----:|
| 📝 Manual, paper-based registration | ⚡ Instant online enrollment |
| 🐌 Slow admin processes | 🚀 Automated course management |
| 📂 Scattered, inconsistent data | 🗃️ Centralized database |
| ❌ Error-prone manual entries | ✅ Accurate, real-time system |
| 😤 Poor student experience | 😊 Smooth, self-service portal |

</div>

---

## 🔮 Future Enhancements

- [ ] 📧 Email notifications for registration confirmation
- [ ] 💳 Payment integration for paid courses
- [ ] 🏅 Downloadable course completion certificates
- [ ] 🔒 Role-based access control (RBAC)
- [ ] 📊 Admin analytics dashboard
- [ ] 📱 Mobile app version

---

## 👤 Author

<div align="center">

<img src="https://avatars.githubusercontent.com/yourusername" width="80" style="border-radius:50%" alt="Author Avatar"/>

### Madhusudhanan S

**B.E. Computer Science and Business Systems**  
Saranathan College of Engineering

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)

</div>

---

## 📄 License

This project is developed for **educational purposes** and is free to use and modify.

---

<div align="center">

**⭐ If this project helped you, give it a star — it means a lot!**

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=yourusername.online-course-registration-system)

</div>
