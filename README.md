<div align="center">

<!-- LOGO / HERO BANNER -->
<br />

<img src="https://img.shields.io/badge/HealthAxis-Full--Stack_Healthcare_Platform-0D7377?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0iTTEyIDZ2NEg4djRoNHY0aDR2LTRoNHYtNGgtNFY2aC00eiIvPjwvc3ZnPg==" alt="HealthAxis" />

<br /><br />

# 🏥 HealthAxis

### *A Premium, Full-Stack Healthcare Appointment Platform*

> Connect patients with verified doctors — instantly, seamlessly, securely.

<br />

[![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)](https://mongodb.com)
[![Express](https://img.shields.io/badge/Express_5-000000?style=flat-square&logo=express&logoColor=white)](https://expressjs.com)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev)
[![Razorpay](https://img.shields.io/badge/Razorpay-02042B?style=flat-square&logo=razorpay&logoColor=3395FF)](https://razorpay.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

<br />

<!-- 🎥 REPLACE THIS COMMENT WITH YOUR VIDEO EMBED -->
<!-- To embed a video from YouTube: -->
<!-- [![Watch the Demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/maxresdefault.jpg)](https://youtu.be/YOUR_VIDEO_ID) -->

> 📸 **Screenshots below** · 🎬 **Video demo coming soon**

<br />

</div>

---

## ✨ What is HealthAxis?

**HealthAxis** is a production-grade healthcare SaaS platform built for modern clinics, hospitals, and independent practitioners. It enables patients to discover, book, and manage appointments with verified doctors — all from a single, beautifully designed interface.

Built with a **full MERN stack**, it includes:
- A **Patient Portal** for booking, payments, and health management
- A **Doctor Panel** for appointment management, analytics, and e-prescriptions
- An **Admin Dashboard** with complete operational control

---

## 🖼️ Screenshots

> 📌 *Replace the image paths below with your actual screenshot files.*

### 🏠 Home Page
<!-- Add your screenshot: ![Home Page](./screenshots/home.png) -->
```
👉 Place your screenshot here: screenshots/home.png
```

### 🩺 Find Doctors
<!-- Add your screenshot: ![Doctors Page](./screenshots/doctors.png) -->
```
👉 Place your screenshot here: screenshots/doctors.png
```

### 📅 Book Appointment
<!-- Add your screenshot: ![Appointment Booking](./screenshots/appointment.png) -->
```
👉 Place your screenshot here: screenshots/appointment.png
```

### 💳 Secure Payment (Razorpay)
<!-- Add your screenshot: ![Payment](./screenshots/payment.png) -->
```
👉 Place your screenshot here: screenshots/payment.png
```

### 👤 Patient Dashboard – My Appointments
<!-- Add your screenshot: ![My Appointments](./screenshots/my-appointments.png) -->
```
👉 Place your screenshot here: screenshots/my-appointments.png
```

### 🩻 Doctor Panel – Analytics Dashboard
<!-- Add your screenshot: ![Doctor Dashboard](./screenshots/doctor-dashboard.png) -->
```
👉 Place your screenshot here: screenshots/doctor-dashboard.png
```

### 🛡️ Admin Panel
<!-- Add your screenshot: ![Admin Dashboard](./screenshots/admin-dashboard.png) -->
```
👉 Place your screenshot here: screenshots/admin-dashboard.png
```

---

## 🚀 Feature Highlights

<table>
<tr>
<td width="50%">

### 👩‍⚕️ Patient Portal
- 🔍 **Smart Doctor Search** — Filter by speciality, name, availability
- 📅 **Real-Time Slot Booking** — Live slot availability, no double-booking
- 💳 **Razorpay Payments** — Seamless, secure online payments
- 💸 **Auto Refund System** — Time-based refund logic (100%, 50%, or 0%)
- ⭐ **Doctor Reviews** — Verified post-appointment star ratings
- 📥 **Download Prescriptions** — Instant PDF download from dashboard
- 🔐 **Email Verification** — Secure OTP-based account verification
- 🔗 **Google OAuth** — One-click sign-in with Google

</td>
<td width="50%">

### 🏥 Doctor & Admin Panels
- 📊 **Analytics Dashboard** — Revenue trends, appointment stats, KPIs
- 📝 **E-Prescription Writer** — Structure prescriptions with medicines, dosages
- 🗓️ **Appointment Management** — Accept, complete, or cancel bookings
- 👨‍💼 **Admin Full Control** — Manage all doctors, appointments, users
- ➕ **Add & Edit Doctors** — Full doctor profile management
- 🔒 **JWT Authentication** — Secure, role-based access for Admin & Doctor
- 📲 **WhatsApp Notifications** — Twilio-powered booking confirmations
- 📧 **Email Notifications** — Automated review requests & OTP emails

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React 19, Vite, TailwindCSS 3, Framer Motion, React Router v7 |
| **Admin Panel** | React 19, Vite, TailwindCSS 3, Recharts (analytics) |
| **Backend** | Node.js, Express 5, MongoDB, Mongoose |
| **Authentication** | JWT, bcrypt, Google OAuth (`google-auth-library`) |
| **Payments** | Razorpay (orders, payments, refunds) |
| **File Storage** | Cloudinary (doctor & patient images) |
| **Notifications** | Nodemailer (email), Twilio (WhatsApp SMS) |
| **PDF Generation** | PDFKit (digital prescriptions) |
| **Deployment** | Vite build, Node.js server |

---

## 📁 Project Structure

```
HealthAxis/
├── 📂 frontend/          # Patient-facing React app (Vite)
│   ├── src/
│   │   ├── components/   # Navbar, Footer, HeroSection, TopDoctors…
│   │   ├── pages/        # Home, Doctors, Appointment, Login, MyProfile…
│   │   └── context/      # AppContext (global state)
│
├── 📂 admin/             # Doctor + Admin React app (Vite)
│   ├── src/
│   │   ├── pages/
│   │   │   ├── Admin/    # Dashboard, AllAppointments, DoctorsList, AddDoctor
│   │   │   └── Doctor/   # DoctorDashboard, DoctorAppointments, DoctorProfile
│   │   └── context/      # AdminContext, DoctorContext
│
└── 📂 backend/           # Node.js + Express API
    ├── controllers/      # userController, doctorController, adminController…
    ├── models/           # userModel, doctorModel, appointmentModel, reviewModel
    ├── routes/           # userRoute, doctorRoute, adminRoute
    ├── middlewares/      # authUser, authAdmin, authDoctor, multer
    └── server.js
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js `v18+`
- MongoDB Atlas or local MongoDB
- Razorpay account (test or live)
- Cloudinary account
- Gmail account (for SMTP)

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/HealthAxis.git
cd HealthAxis
```

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file in `/backend`:

```env
# Database
MONGODB_URI=your_mongodb_connection_string

# Auth
JWT_SECRET=your_super_secret_jwt_key

# Admin Credentials
ADMIN_EMAIL=admin@healthaxis.com
ADMIN_PASSWORD=your_admin_password

# Cloudinary
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_SECRET_KEY=your_api_secret

# Payments
RAZORPAY_KEY_ID=rzp_test_xxxxxxxxxxxxx
RAZORPAY_KEY_SECRET=your_razorpay_secret

# Email (SMTP)
EMAIL_FROM=your_gmail@gmail.com
SMTP_USER=your_gmail@gmail.com
SMTP_PASS=your_gmail_app_password

# Google OAuth
GOOGLE_CLIENT_ID=your_google_client_id.apps.googleusercontent.com

# WhatsApp (Twilio) — Optional
TWILIO_ACCOUNT_SID=ACxxxxxxxxxxxxxxxxxxxxxxxxx
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_WHATSAPP_NUMBER=whatsapp:+14155238886
```

```bash
npm run server
```

### 3. Setup Frontend

```bash
cd ../frontend
npm install
```

Create a `.env` file in `/frontend`:
```env
VITE_BACKEND_URL=http://localhost:4000
VITE_RAZORPAY_KEY_ID=rzp_test_xxxxxxxxxxxxx
VITE_GOOGLE_CLIENT_ID=your_google_client_id.apps.googleusercontent.com
```

```bash
npm run dev
```

### 4. Setup Admin Panel

```bash
cd ../admin
npm install
```

Create a `.env` file in `/admin`:
```env
VITE_BACKEND_URL=http://localhost:4000
```

```bash
npm run dev
```

---

## 🌐 Running URLs

| App | URL |
|---|---|
| 🏥 Patient Frontend | `http://localhost:5173` |
| 🛡️ Admin / Doctor Panel | `http://localhost:5174` |
| ⚙️ Backend API | `http://localhost:4000` |

---

## 💸 Refund Policy Logic

HealthAxis includes a smart, automatic refund system integrated with Razorpay:

| Time Before Appointment | Refund |
|---|---|
| More than **24 hours** | ✅ **100% Full Refund** |
| Between **12–24 hours** | 🟡 **50% Partial Refund** |
| Less than **12 hours** | ❌ **No Refund** |

---

## 🌟 Why This Project Stands Out

This is not a template — it's a **fully custom-built**, production-grade platform that mirrors real-world healthcare SaaS products. Every screen, API, and feature has been hand-crafted:

- **Design:** Premium SaaS aesthetic with teal medical palette, Inter typography, smooth micro-animations
- **Security:** JWT-secured routes, bcrypt hashing, email OTP, Google OAuth
- **Business Logic:** Razorpay refunds, verified reviews (1 per appointment), slot deduplication
- **Developer Experience:** Clean architecture, organized controllers, reusable React components

---

## 📬 Contact the Developer

> Built with ❤️ by **Kartikeya Nainkhwal**

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kartikeya@example.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/YOUR_GITHUB)

---

<div align="center">

**⭐ Star this repo if you found it impressive!**

*© 2026 HealthAxis Technologies · Built for the modern healthcare ecosystem*

</div>


