# 🎪 EventHub Management System

Full-stack Event Management System — Angular 17 + Node.js + Express + MongoDB

## 🚀 Quick Start

### Step 1 — Backend
```bash
cd backend
npm install
# Make sure MongoDB is running locally
npm run dev
```
Backend runs on: http://localhost:5000

### Step 2 — Seed Demo Data (Do Once)
Open browser: http://localhost:5000/api/seed

### Step 3 — Frontend
```bash
cd frontend
npm install
npm start
```
Frontend runs on: http://localhost:4200

---

## 🔑 Demo Credentials
| Role | Email | Password |
|------|-------|----------|
| Admin | admin@eventhub.com | admin123 |

---

## 📁 Project Structure
```
eventhub/
├── backend/
│   ├── config/db.js
│   ├── middleware/auth.js
│   ├── models/ (User, Event, Participant, Feedback)
│   ├── routes/ (auth, events, admin, feedback)
│   └── server.js
└── frontend/src/app/
    ├── admin/ (dashboard, users, event-list, participants, feedback, queries)
    ├── pages/ (home, events, event-detail, auth, queries)
    ├── services/ (auth, event, admin)
    ├── guards/ (authGuard, adminGuard)
    └── shared/navbar/
```

## ✨ Features
### Public Pages
- Home with hero search, event grid, categories
- Events page with location + category filter
- Event detail with UPI payment simulation
- Login / Register with JWT auth
- My Queries page for users

### Admin Panel (/admin)
- Dashboard with stats, revenue, category chart
- Users CRUD management
- Events CRUD management
- Participants list
- Feedback management with star ratings
- Query resolution system

## 🛠 Tech Stack
- **Frontend:** Angular 17, Standalone Components, TypeScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose
- **Auth:** JWT + bcryptjs
- **Styling:** Custom CSS with Google Fonts (Syne + DM Sans)
