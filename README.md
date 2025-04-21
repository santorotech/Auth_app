# Flask Authentication App

A simple user authentication system built with Flask and SQLite. This app allows users to sign up, log in, and log out securely using hashed passwords.

## Features

- User sign up with unique username
- Passwords stored securely using hashing
- User login with session management
- SQLite database integration
- Simple HTML interface

## Project Structure

Auth_app/
│

├── app.py               # Main Flask application with routes and logic

├── database.db          # SQLite database (auto-created)

│

└── templates/     # Folder for HTML templates
    │
    ├── login.html       # Login page
    │
    └── signup.html      # Sign-up page
