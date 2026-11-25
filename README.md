<div align="center">

# 🏋️‍♂️ GymFitness — Premium Fitness Management Platform

[![Live Demo](https://img.shields.io/badge/Demo-Live_Website-22c55e?style=for-the-badge&logo=vercel&logoColor=white)](https://gym-website-seven-eta.vercel.app)
[![Watch Video Walkthrough](https://img.shields.io/badge/Video-1080p_Walkthrough-ff0000?style=for-the-badge&logo=youtube&logoColor=white)](docs/assets/walkthrough.mp4)
[![MERN Stack](https://img.shields.io/badge/Stack-MERN-blue.svg?style=for-the-badge)](https://www.mongodb.com/mern-stack)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![Developer](https://img.shields.io/badge/Developer-Sahani%20Tripurari-orange?style=for-the-badge&logo=github)](https://github.com/sahaniTripurari)

<br/>

<!-- ================= RESPONSIVE HERO VIDEO / SHOWCASE ================= -->
<a href="docs/assets/walkthrough.mp4" target="_blank" title="Click to Watch Full 1080p Video Walkthrough">
  <img src="docs/assets/preview.gif" alt="GymFitness Live Walkthrough Preview" width="100%" style="max-width: 860px; border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.35);" />
</a>

<p align="center">
  <sub>🎬 <b>Live Animated Walkthrough</b> • <i>Click preview above or <a href="docs/assets/walkthrough.mp4"><b>watch full 1080p walkthrough video</b></a></i> • 🔗 <a href="https://gym-website-seven-eta.vercel.app"><b>Open Live App</b></a></sub>
</p>

</div>

---

A high-end, full-stack MERN application designed for modern fitness centers. This project showcases a premium UI/UX experience, seamless data integration, class scheduling, and member management features.

🔗 **Live Deployment:** [gym-website-seven-eta.vercel.app](https://gym-website-seven-eta.vercel.app)

---

## 🌟 Key Features

- **💎 Premium UI/UX**: Sophisticated, dark-aesthetic responsive design built with React 19, Vite, and Framer Motion.
- **📅 Class Scheduling**: Real-time management and filtering of gym classes and schedules.
- **💪 Trainer Booking**: Member interface to discover and book certified professional trainers.
- **💳 Membership Plans**: Dynamic membership tiers with clear feature comparisons.
- **📊 User Dashboard**: Personalized member progress tracking, body metrics, and membership status.
- **🛠 Admin Management**: Comprehensive backend controls for managing classes, bookings, and members.
- **🔒 Secure Authentication**: Protected routes with JSON Web Tokens (JWT) and HTTP-only cookies.

---

## 🚀 Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | React 19, Vite, Framer Motion, Styled Components, Axios |
| **Backend** | Node.js, Express 4, RESTful Architecture, JWT, Cookie-Parser, Compression |
| **Database** | MongoDB with Mongoose ODM |
| **Payment** | Razorpay Gateway Integration (with Dev/Mock fallback) |
| **Deployment**| Vercel |

---

## 🛠️ Installation & Local Setup

### 1. Clone the repository
```bash
git clone https://github.com/sahaniTripurari/GymWebsite.git
cd GymWebsite
```

### 2. Backend Setup
```bash
cd backend
npm install
cp .env.example .env   # On Windows: copy .env.example .env
```
Fill in your MongoDB URI and JWT Secret in `.env`:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLIENT_URL=http://localhost:5173
```
Start the backend server:
```bash
npm run dev
```

### 3. Frontend Setup
Open a new terminal window:
```bash
cd frontend
npm install
cp .env.example .env   # On Windows: copy .env.example .env
npm run dev
```
> The frontend application will run at: `http://localhost:5173`  
> The backend API will run at: `http://localhost:5000`

---

## 📁 Project Architecture

```
GymWebsite/
├── docs/
│   └── assets/              # Showcase video, preview GIF & poster
├── backend/
│   ├── src/
│   │   ├── config/          # Database configuration (db.js)
│   │   ├── controllers/     # Auth, booking, program, trainer logic
│   │   ├── middleware/      # Auth & protect middleware
│   │   ├── models/          # Mongoose Schemas (User, Booking, Membership, etc.)
│   │   ├── routes/          # Express API route handlers
│   │   └── server.js        # Server entry point
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/      # UI sections (Hero, Navbar, Schedule, etc.)
│   │   ├── context/         # AuthContext
│   │   ├── pages/           # Dashboard, Admin, Profile, Programs, Trainers
│   │   └── api.js           # Axios client configured with base URL
│   └── package.json
└── README.md
```

---

## 👨‍💻 Developer & Contact

**Sahani Tripurari** — Full-Stack Developer  
- **GitHub:** [@sahaniTripurari](https://github.com/sahaniTripurari)  
- **Email:** sahanitrirpurari@gmail.com  
- **Portfolio / Live App:** [GymFitness Live](https://gym-website-seven-eta.vercel.app)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
