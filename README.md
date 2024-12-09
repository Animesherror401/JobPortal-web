# User Authentication Project

This project demonstrates a basic user authentication system using Firebase. It includes functionalities for user registration and login. The project is built using HTML, CSS, and JavaScript with Firebase as the backend for authentication and real-time database storage.

---

## Table of Contents
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Setup Instructions](#setup-instructions)
4. [File Structure](#file-structure)
5. [How to Use](#how-to-use)
6. [Firebase Configuration](#firebase-configuration)
7. [Database Rules](#database-rules)
8. [Future Improvements](#future-improvements)

---

## Features
- User registration with email and password.
- User login with email and password.
- Real-time database integration to store user data (e.g., username and email).
- Simple, responsive user interface.

---

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Firebase Authentication, Firebase Realtime Database
- **Firebase SDK Version**: 9.6.1

---

## Setup Instructions
1. Clone or download the project files to your local machine or open in Replit.
2. Ensure you have Firebase set up with the following services:
   - Authentication
   - Realtime Database
3. Add your Firebase configuration details to the `firebase-config.js` file.
4. Update the database rules in the Firebase Console (see [Database Rules](#database-rules)).
5. Run the project using a local server or deploy it using Replit.

---

## File Structure

---

## How to Use
1. **Registration**:
   - Navigate to `register.html`.
   - Enter a username, email, and password to register.
   - The user data will be stored in the Firebase Realtime Database.

2. **Login**:
   - Navigate to `index.html`.
   - Enter your email and password to log in.
   - Successful login will show a success message.

---

## Firebase Configuration
Replace the placeholder in `firebase-config.js` with your Firebase project configuration:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  databaseURL: "YOUR_DATABASE_URL",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
  measurementId: "YOUR_MEASUREMENT_ID"
};

// Initialize Firebase
firebase.initializeApp(firebaseConfig);
firebase.analytics();
