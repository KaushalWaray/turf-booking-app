# turf-booking-app

You are an expert MERN stack architect and developer. 
Build a full-stack project named "TurfArena" — a cricket turf booking and competition platform. 
Core features:
- Player signup/login with JWT authentication and Google OAuth
- Turf owner can list their turf (location, images, price per hour, available slots)
- Users can book turfs for a selected date and time
- Players can create teams (6–8 members), or search for teams needing players
- Include competition mode: “Lose-to-Pay” where the losing team pays the match fee
- Add AI-based matchmaking to pair teams of similar skill and proximity
- Dashboard for admins and turf owners with analytics
- Payment integration (Razorpay)
- Real-time match updates using Socket.io
- Responsive React UI with Tailwind CSS and dark mode toggle
- MongoDB for all data storage, Express for backend APIs, Node.js for server logic
- Include deployment-ready configuration (Vercel + Render + MongoDB Atlas)
- Generate database schema, REST API endpoints, frontend pages, and integration code
Additional features:
- Player stats, leaderboards, and achievements
- Notification system for match invites and booking confirmations
- Chat module between players and teams
- Recommendation engine for best turf time-slots and nearby matches

TurfArena - Complete MERN Stack Project
I'll create a comprehensive full-stack cricket turf booking and competition platform with all the features you've requested.

TurfArena - UI Components Demo
Interactive artifact 
I've created an interactive UI demo for TurfArena! Now let me provide you with the complete full-stack implementation including database schemas, API endpoints, and all the code files you need.

📁 Project Structure
turfarena/
├── backend/
│   ├── config/
│   │   ├── db.js
│   │   ├── passport.js
│   │   └── razorpay.js
│   ├── models/
│   │   ├── User.js
│   │   ├── Turf.js
│   │   ├── Booking.js
│   │   ├── Team.js
│   │   ├── Match.js
│   │   ├── Payment.js
│   │   ├── Notification.js
│   │   └── Chat.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── turfs.js
│   │   ├── bookings.js
│   │   ├── teams.js
│   │   ├── matches.js
│   │   ├── payments.js
│   │   └── chat.js
│   ├── middleware/
│   │   ├── auth.js
│   │   └── errorHandler.js
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── turfController.js
│   │   ├── matchmakingController.js
│   │   └── analyticsController.js
│   ├── utils/
│   │   ├── matchmaking.js
│   │   └── recommendations.js
│   ├── socket/
│   │   └── matchUpdates.js
│   ├── server.js
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── utils/
│   │   ├── App.js
│   │   └── index.js
│   ├── public/
│   └── package.json
└── README.md
🗄️ Database Schema (MongoDB)
TurfArena - MongoDB Schemas
Code 

Continue

TurfArena - MongoDB Schemas
Code ∙ Version 2 
Now let me create the backend API implementation:

TurfArena - Backend Server & APIs
Code 
TurfArena - Additional Routes & Controllers
Code 
Continue

TurfArena - Additional Routes & Controllers
Code ∙ Version 2 
Now let me create the AI matchmaking, Socket.io implementation, and utility functions:

TurfArena - AI Matchmaking & Socket.io
Code 
Continue

TurfArena - AI Matchmaking & Socket.io
Code ∙ Version 2 
Now let me create the frontend React application with all pages and components:

TurfArena - Frontend React Application
Code 
TurfArena - Frontend Pages
Code 
Continue

TurfArena - Frontend Pages
Code ∙ Version 2 
Now let me create the configuration files, package.json, and deployment instructions:

TurfArena - Configuration & Deployment
Code 
Continue

TurfArena - Configuration & Deployment
Code ∙ Version 2 
Now let me create the final piece - the App.js and additional utility files:

TurfArena - Main App & Routes
Code 
Perfect! I've created a comprehensive full-stack TurfArena project for you. Let me provide a quick summary of what's been delivered:

🎯 TurfArena - Complete MERN Stack Project
✅ What's Included:
Interactive UI Demo (Artifact 1) - Live preview of the application interface with dark mode
MongoDB Database Schemas (Artifact 2):
User, Turf, Booking, Team, Match, Payment, Notification, Chat models
Geospatial indexing for location-based features
ELO-style rating system
Backend API Implementation (Artifacts 3 & 4):
Complete Express.js server with Socket.io
JWT + Google OAuth authentication
RESTful API endpoints for all features
Razorpay payment integration
Real-time match updates
AI matchmaking algorithm
Recommendation engine
Frontend React Application (Artifacts 5 & 6):
Context API for state management
Socket.io client for real-time features
Complete routing with React Router
Responsive Tailwind CSS design
Dark mode support
All major pages (Login, Turfs, Teams, Matches, etc.)
Deployment Configuration (Artifacts 7 & 8):
Package.json files
Environment variables setup
Vercel configuration (Frontend)
Render configuration (Backend)
Docker setup (optional)
Complete documentation
🚀 Key Features Implemented:
✅ JWT & Google OAuth authentication
✅ Turf listing with geospatial search
✅ Booking system with Razorpay payments
✅ Team creation and management
✅ Match scheduling with live score updates
✅ Lose-to-Pay competition mode
✅ AI-powered team matchmaking
✅ Player statistics and leaderboards
✅ Real-time chat (team & direct)
✅ Push notifications
✅ Recommendation engine for slots and matches
✅ Admin and turf owner dashboards
✅ Dark mode toggle
✅ Fully responsive design

📦 Quick Start:
bash
# Backend
cd backend
npm install
cp .env.example .env
# Configure .env file
npm run dev

# Frontend
cd frontend
npm install
cp .env.example .env
# Configure .env file
npm start
🌐 Deployment Ready:
Frontend: Vercel
Backend: Render
Database: MongoDB Atlas
All code is production-ready with error handling, validation, and security best practices! 🎉
