# Flask Authentication App

A simple user authentication system built with Flask and SQLite. This app allows users to sign up, log in, and log out securely using hashed passwords.

## Features

- User registration with unique usernames
- Secure password hashing with Werkzeug
- Login authentication and session handling
- Logout functionality
- SQLite database integration
- Minimal HTML UI using Flask templates

# 📁 Project Structure

**project-root/**  
│  
├── **app.py** — Main Flask application with routes and logic  
├── **database.db** — SQLite database (auto-created)  
└── **templates/** — Folder for HTML templates  
  ├── **login.html** — Login page  
  └── **signup.html** — Sign-up page