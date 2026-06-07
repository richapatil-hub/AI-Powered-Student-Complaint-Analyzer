# 🎓 AI-Powered Student Complaint Analyzer

A full-stack web application that allows students to submit complaints and administrators to manage and resolve them — with AI-powered automatic complaint categorization.

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## ✨ Features

- 🔐 **Student & Admin Authentication** via Firebase Auth
- 📝 **Complaint Submission** with title, description, and category
- 🤖 **AI Auto-Classification** — automatically categorizes complaints into: Academics, Hostel, IT Infrastructure, Administration, Maintenance, Examination
- 📊 **Student Dashboard** — track complaint status in real-time
- 🛡️ **Admin Dashboard** — view all complaints, update status, and visualize data with charts
- 📈 **Analytics** — category and status bar charts for admins
- ⚡ **Real-time Updates** using Firebase Realtime Database

---

## 🗂️ Project Structure

```
complaint-analyzer/
├── web-dashboard/
│   ├── login.html           # Student login & register
│   ├── student-dashboard.html  # Student complaint submission & tracking
│   ├── admin-login.html     # Admin login portal
│   └── admin-dashboard.html # Admin complaint management
├── ml-model/
│   └── classifier.py        # Python ML classifier (coming soon)
├── screenshots/
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/AI-Powered-Student-Complaint-Analyzer.git
cd AI-Powered-Student-Complaint-Analyzer
```

### 2. Open in browser
Simply open `web-dashboard/login.html` in your browser — no server needed!

### 3. Create an Admin Account
- Register as a student first via `login.html`
- Go to Firebase Console → Realtime Database
- Find your user under `users/YOUR_UID`
- Change `role: "student"` to `role: "admin"`
- Now login via `admin-login.html`

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Authentication | Firebase Authentication |
| Database | Firebase Realtime Database |
| AI Classification | Keyword-based NLP classifier |
| Hosting | Firebase Hosting / GitHub Pages |

---

## 📸 Screenshots

> Add screenshots of your app here

---

## 🤖 AI Classification

The system automatically classifies complaints into categories using keyword-based NLP:

| Category | Keywords Detected |
|---|---|
| Academics | exam, marks, grade, professor, syllabus |
| Hostel | room, mess, food, warden, dormitory |
| IT Infrastructure | wifi, internet, computer, lab, network |
| Administration | fee, office, certificate, admission |
| Maintenance | repair, broken, leak, electricity, fan |
| Examination | hall ticket, timetable, malpractice |

---

## 👩‍💻 Author

**Richa** — Final Year Engineering Student  
Project developed as part of Final Year Project (2025–26)

---

## 📄 License

MIT License — feel free to use and modify.
