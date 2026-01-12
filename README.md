# Visionary-Facial-Authentication-System

This project is a real-time face recognition authentication system using Flask (Python) for the backend and React for the frontend. It leverages deep learning-based face embeddings to identify users based on their facial features in live video streams.
The system provides two types of user roles:
  - User and Admin: Both can register and log in using face recognition.
  - It offers secure, contactless authentication through a webcam and stores login logs for accountability.


  ## Features
 - Real-time face authentication using WebSocket (Socket.IO)
 - Registration of new users with name and image
 - Image-based face recognition using facial embeddings
 - Fast and accurate recognition with smooth frontend integration
 - Uses FaceNet model via DeepFace for high-quality embeddings
 - Frontend built with React using face-api.js for capturing and sending images
 - User Dashboard: View personal login logs with date and time
 - Admin Dashboard: View all registered users,Track all login events,Delete users when needed

## Technologies Used
 - Backend: Flask, Flask-SocketIO,OpenCV
 - Frontend: React, face-api.js, Socket.IO-client, Webcam, Tailwind CSS
 - Notifications: React-hot-toast
 - Model: FaceNet (for generating facial embeddings)
   

## Installation
1. Clone the repository
   
2. Navigate to the project directory:
   ```bash
   cd Visionary-Advanced-Image-Recognition-for-the-Next-Era
   ```
3. Navigate to the backend/ directory:
   ```bash
   cd backend
   ```
4. Activate virtual environment(windows):
   ```bash
   venv\Scripts\activate
   ```
5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
6. Run the backend:
   ```bash
   python app.py
   ```
7. Navigate to the frontend/ directory:
   ```bash
   cd frontend
   ```  
8. Install dependencies:
   ```bash
   npm install
   ```
9. Start the development server:
   ```bash
   npm run dev
   ```






