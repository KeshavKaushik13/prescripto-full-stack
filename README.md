# 🏥 Prescripto – Doctor Appointment Booking System

## Links

- 🔗 Live Demo: https://prescripto-full-stack-nu.vercel.app
- 🔗 Admin Dashboard: https://prescripto-full-stack-1nsh.vercel.app/admin-dashboard
- 🔗 GitHub: https://github.com/KeshavKaushik13/prescripto-full-stack
  
## Admin Test Credentials

Use the following credentials to access the admin dashboard for testing:

**Email:** admin@example.com  
**Password:** greatstack123

---

## 📌 Overview

Prescripto is a full-stack doctor appointment booking system designed for hospitals and individual practitioners.
It enables seamless interaction between **Patients, Doctors, and Admins** through a secure, role-based platform.

The system implements **JWT-based authentication** and provides dedicated dashboards for each user type to manage appointments, profiles, and workflows efficiently.

---

## 🚀 Features

### 👤 Patient

* Register and login securely
* Browse available doctors
* Book appointments
* View and manage booked appointments

### 👨‍⚕️ Doctor

* Secure login with role-based access
* View scheduled appointments
* Track earnings
* Update profile information

### 🛠 Admin

* Manage all appointments
* Add/update/remove doctors
* Monitor system activity through dashboard

---

## 🔐 Authentication & Authorization

* Implemented **JWT (JSON Web Tokens)** for secure authentication
* Role-based access control:

  * Patient
  * Doctor
  * Admin
* Protected routes for each user type

---

## 🧱 Tech Stack

**Frontend**

* React.js
* Tailwind CSS

**Backend**

* Node.js
* Express.js

**Database**

* MongoDB

**Authentication**

* JWT (JSON Web Tokens)

**Deployment**

* Frontend: Vercel
* Backend: Render

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/KeshavKaushik13/prescripto-full-stack.git
cd prescripto-full-stack
```

### 2️⃣ Setup Backend

```bash
cd backend
npm install
npm run server
```

### 3️⃣ Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 📂 Project Structure

```
prescripto-full-stack/
│── frontend/        # React client
│── backend/         # Node.js + Express server
│── models/          # MongoDB schemas
│── routes/          # API routes
│── controllers/     # Business logic
```

---

## 🌟 Key Highlights

* Role-based multi-user system (Patient, Doctor, Admin)
* Secure authentication using JWT
* Scalable full-stack architecture
* Real-world healthcare workflow simulation

---

## 🚧 Future Improvements

* Email/SMS notifications
* Real-time appointment updates
* Doctor availability scheduling system

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📧 Contact

For any queries or feedback, feel free to reach out.

---

⭐ If you found this project useful, consider giving it a star!
