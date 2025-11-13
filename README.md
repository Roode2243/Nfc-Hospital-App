Project: NFC Hospital App Prototype

Stack
- Mobile: Flutter
- Backend: Node.js + Express
- DB: MongoDB

Quick start
1. Start backend
   cd backend
   npm install
   cp .env.example .env
   fill MONGO_URI and JWT_SECRET
   npm run dev

2. Start mobile (Flutter)
   cd mobile
   flutter pub get
   flutter run

Goals
- Phone sends encrypted patient token via NFC
- Hospital app uses token to request records from backend
- Patient and hospital have separate logins and access levels
