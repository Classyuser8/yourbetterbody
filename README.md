# yourbetterbody
# 💪 YourBetterBody – Full-Stack Fitness Coaching Platform

**YourBetterBody** is a full-featured fitness coaching platform built for personal trainers and their clients. It includes tools for workout programming, nutrition planning, habit tracking, progress logging, and in-app communication. Designed to streamline both in-person and online coaching, YourBetterBody empowers trainers to scale their business and deliver measurable results.

---

## 🧩 Core Features

### 🔐 User Authentication & Roles
- JWT-based login for coaches and clients
- Role-based access control and secure sign-up/logout

### 🏋️‍♂️ Workout Module
- Custom workout programs with videos, sets, reps, RPE, and notes
- Supersets, circuits, tempo, and substitutions
- Logging and workout history tracking

### 🥗 Nutrition Module
- Meal plan templates with macros, calories, recipes, and food swaps
- Coach-assigned plans and optional daily food logging
- Future integration: barcode scanning or image recognition

### 📊 Progress & Metrics
- Weekly check-ins (weight, photos, measurements, notes)
- Graph-based visualization of progress over time

### ✅ Habit Tracker
- Daily habit checklists with streaks and completion history
- Coach-assigned or user-created habits

### 🎓 Education Hub
- Embedded videos, eBooks, and locked/unlocked lessons
- Use as upsell for digital resources or premium clients

### 💬 In-App Messaging
- Client-coach chat with push notifications for updates, check-ins, etc.

### 🖥️ Coach Dashboard (Web)
- Assign workouts, track client progress, manage subscriptions

### 💳 Subscriptions & Payments
- Stripe integration for weekly/fortnightly billing
- Auto access control based on active payment status

---

## 🛠️ Tech Stack

| Layer      | Stack                              |
|------------|------------------------------------|
| Mobile App | React Native (Expo)                |
| Web Admin  | React                              |
| Backend    | Node.js + Express + MongoDB        |
| Auth       | JWT + bcrypt                       |
| Payments   | Stripe Checkout + Webhooks         |
| Storage    | Cloudinary                         |
| Messaging  | Firebase Cloud Messaging (planned) |
| Hosting    | Vercel / Render / Firebase         |

---

## 🧠 My Role

As the solo developer and founder of this platform, I’m responsible for:
- System architecture and database schema
- Frontend UI/UX in React Native and React Web
- RESTful backend APIs (Node.js + Express)
- Stripe subscription logic and webhook handling
- Admin dashboard and business automation flow

---

## 🗂️ Documentation

| Doc Type        | File Path                         |
|----------------|-----------------------------------|
| ERD Diagram     | `docs/ERD.md`                     |
| API Reference   | `docs/API.md`                     |
| Dev Roadmap     | `docs/Roadmap_Issues.md`          |
| Mockups         | `design/wireframes/`              |
| Screenshots     | `public/screenshots/`             |

---

## 🚧 Roadmap Preview

- [x] User authentication, role system, and basic coach tools
- [x] Workout and check-in logging with backend tracking
- [x] Stripe integration for client subscriptions
- [ ] Nutrition module with meal plans and logging
- [ ] Push notifications (via Firebase Cloud Messaging)
- [ ] Education Hub and content upsells

---
