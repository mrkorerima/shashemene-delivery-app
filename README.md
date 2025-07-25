# Shashemene Delivery App 🚚🇪🇹

A location-based delivery service app built specifically for **Shashemene, Ethiopia**, supporting three user roles: **Consumers**, **Drivers**, and **Admins**.

---

## 🧱 Project Structure
shashemene-delivery-app/
│
├── consumer-app/          # React or Flutter app for customers
│   ├── public/
│   ├── src/
│   ├── .env
│   └── package.json
│
├── driver-app/            # Mobile-first app for drivers
│   ├── src/
│   ├── assets/
│   ├── .env
│   └── package.json
│
├── admin-dashboard/       # Web admin panel
│   ├── public/
│   ├── src/
│   ├── .env
│   └── package.json
│
├── backend/               # Server-side code (Express, Firebase Functions, etc.)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── index.js
│   └── package.json
│
├── firebase-config/       # Firebase setup and rules
│   ├── firestore.rules
│   ├── firebase.json
│   ├── functions/
│   └── .env
│
├── .gitignore             # Ignore node_modules, envs, etc.
├── README.md              # Project overview and instructions
└── LICENSE                # (Optional: MIT, Apache 2.0, etc.)

