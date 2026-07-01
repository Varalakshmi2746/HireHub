# 🚀 HireHub — Full-Stack MERN Job Portal 2025

HireHub is a professional role-based platform designed to connect **Recruiters** and **Job Seekers**. Built using the **MERN Stack**, it provides a seamless experience for posting jobs, managing applicants, and tracking career opportunities in real-time.

---

## ✨ Key Features

### 👨‍💼 For Job Seekers
- 📊 Personalized Dashboard to track application status.
- 🔍 Browse available job listings.
- 📩 Apply for jobs with a single click.
- 📌 Track application progress from **Applied → Interview → Hired**.

### 🏢 For Recruiters
- ➕ Create, update, and delete job postings.
- 👥 Applicant Tracking System (ATS).
- 📋 View candidate profiles and manage hiring.
- 🔒 Dedicated recruiter dashboard with secure access.

---

## ⚙️ Technical Highlights

- 🔐 Role-Based Access Control (RBAC)
- 🔑 Secure Authentication using JWT & bcrypt
- ⚡ RESTful API Architecture
- ⚛️ React.js with Redux State Management
- 📱 Fully Responsive Mobile-First Design

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Frontend** | React.js, Redux, HTML5, CSS3, JavaScript |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Authentication** | JWT, bcrypt |
| **API** | RESTful APIs |
| **Tools** | Git, GitHub, VS Code, Postman |

---

## 📂 Project Structure

```text
HireHub/
│
├── frontend/
├── backend/
├── README.md
└── package.json
```

---

## 🚀 Setup & Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Varalakshmi2746/HireHub.git
```

### 2️⃣ Install Dependencies

Backend

```bash
cd backend
npm install
```

Frontend

```bash
cd frontend
npm install
```

### 3️⃣ Configure Environment Variables

Create a **.env** file.

```env
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
PORT=5000
```

### 4️⃣ Run the Application

Backend

```bash
npm start
```

Frontend

```bash
npm start
```

---

## 📡 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register a new user |
| POST | `/api/auth/login` | Login user |
| GET | `/api/jobs` | Fetch all jobs |
| POST | `/api/jobs` | Create a job (Recruiter) |
| POST | `/api/apply` | Apply for a job |

---

## 🌟 Future Enhancements

- 🤖 AI Job Recommendation
- 📄 Resume Upload
- 📧 Email Notifications
- 📅 Interview Scheduling
- 💬 Real-Time Chat
- 🔔 Push Notifications

---

## 👩‍💻 Author

**Varalakshmi Maridu**

- 🌐 GitHub: https://github.com/Varalakshmi2746
- 💼 LinkedIn: https://www.linkedin.com/in/varalakshmi-maridu-732729353/

---

⭐ **If you found this project useful, please consider giving it a Star!**
