📱 Downtown Lobby Beta – Project Overview

🧠 Introduction

Downtown Lobby Beta is a modern hybrid mobile application designed to serve as a centralized digital platform for school communication and student engagement.

The app allows students to easily access:

- Announcements
- School events
- News and posts
- Timetables (weekly & exam)
- Entertainment content (videos & media)

All content is dynamically managed through a separate web-based admin panel, ensuring real-time updates without needing to rebuild the app.

---

🎯 Project Goal

The goal of this project is to create a real-world scalable app system similar to platforms like social media apps, where:

- The frontend (mobile app) displays content
- The backend (server + database) manages logic and data
- The admin panel (web dashboard) controls everything

---

🧩 System Architecture

This project follows a full-stack architecture:

1. Frontend (Mobile App)

- Built using React
- Converted into Android APK using Capacitor
- Displays content fetched from backend APIs

2. Backend (Server + Database)

- Custom backend (Node.js or similar)
- Handles APIs, data storage, and file management
- Manages app version control and updates

3. Admin Panel (Web Dashboard)

- Secure login system
- Allows admin to manage all app content
- Acts as the “control center” of the system

---

🔥 Key Features

📢 Announcements

- Real-time updates from backend
- Display important school notices

---

📅 Events

- List of upcoming school activities
- Clean and simple UI

---

📰 News & Posts

- Feed-style content
- Supports images and text

---

🕒 Timetable System

- Displays timetable as large images
- Supports:
  - Weekly timetable
  - Exam timetable
- Automatically updates when changed in admin panel

---

⭐ Entertainment Section

- Dedicated section for videos
- Built-in video player
- Streams content uploaded by admin

---

🔔 Remote App Update System

- App checks backend for latest version
- If outdated:
  - Shows update popup
  - Provides APK download link

---

♻️ Storage Cleanup System

- When content is deleted:
  - Associated files (images/videos) are also removed
- Prevents storage overload
- Keeps backend optimized

---

⚙️ Hybrid App Concept

This app uses a Hybrid Architecture:

- The mobile app is like a container (Android app)
- The UI is built using web technologies (React)
- Capacitor acts as a bridge between them

📦 Bundle Assets

All HTML, CSS, and JavaScript files are packaged inside the APK, allowing:

- Faster loading
- Partial offline functionality

---

🏗️ Build Environment

The system uses:

- Node.js & pnpm (dependency management)
- Java (OpenJDK 21)
- Gradle (8.8)
- Android SDK (Target 35)
- Capacitor (bridge between web & Android)

---

🧪 Build Process Overview

1. "pnpm build"
   
   - Compiles React app into optimized "/dist" folder

2. "npx cap sync"
   
   - Syncs web app into Android project

3. "./gradlew assembleDebug"
   
   - Builds the APK file for testing

---

🎨 Design Philosophy

- Clean and modern UI
- Minimal color scheme (black, white, gold accents)
- Smooth animations and transitions
- Card-based layout for simplicity and readability

---

⚠️ Important Principles

- No hardcoded data in the app
- All content must come from backend
- Admin panel controls everything
- System must be scalable and maintainable

---

🚀 Expected Outcome

A complete working system including:

- Backend server
- Admin panel (web dashboard)
- Hybrid Android app (APK)
- Fully dynamic content system

---

End of README
