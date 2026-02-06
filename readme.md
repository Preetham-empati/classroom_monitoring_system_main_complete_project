🎓 Student Attentiveness Monitoring System

A real-time AI-powered classroom monitoring web application built using Flask and Computer Vision to analyze, track, and visualize student attentiveness during classroom sessions.

This system assists educators in understanding student engagement by detecting inattentive behaviors and generating insightful analytics and automated reports.

🚀 Project Overview

The Student Attentiveness Monitoring System leverages advanced computer vision techniques to monitor student behavior in real time using a live video feed.

The system is capable of:

Identifying and recognizing students using facial recognition

Detecting head pose to determine attention direction

Analyzing eye state to identify drowsiness or sleepiness

Monitoring hand movement and possible phone usage

Classifying attentiveness levels

Logging data for analytics and reporting

Sending automated email reports to faculty

🧠 Core Capabilities

Real-time Face Detection & Recognition
Identifies students using pre-generated face encodings.

Head Pose Estimation
Detects whether students are looking forward, down, or away.

Eye State Detection
Identifies drowsiness using Eye Aspect Ratio (EAR).

Hand Detection
Tracks hand movement to monitor possible phone usage.

Attentiveness Scoring System
Combines multiple behavioral parameters to classify student attentiveness.

Dashboard Analytics
Displays student-wise and class-wise attentiveness trends.

Automated Email Reports
Sends attentiveness summaries to teachers and administrators.

🛠️ Tech Stack
🔙 Backend

Flask

Flask-SQLAlchemy

Flask-Login

Flask-Bcrypt

Flask-Mail

👁️ Computer Vision & AI

OpenCV

MediaPipe

face_recognition

NumPy

SciPy

📊 Data Processing & Visualization

Pandas

Plotly / Plotly.js

🗄️ Database

SQLite

SQLAlchemy

🌐 Frontend

HTML

CSS

JavaScript

classroom_monitoring_system_main_complete_project/
│
├── app.py # Main Flask application
├── create_dataset.py # Capture student facial images
├── encode_faces.py # Generate facial encodings
├── requirements.txt # Project dependencies
│
├── static/
│ ├── css/ # Stylesheets
│ ├── js/ # JavaScript files
│ └── images/ # Saved frames / screenshots
│
├── templates/
│ ├── login.html
│ ├── register.html
│ ├── dashboard.html
│ ├── livestream.html
│ ├── timetable.html
│ └── reports.html
│
├── dataset/ # Student face image dataset
├── encodings/ # Generated face encodings
└── database.db # SQLite database

✨ Features

✅ Secure user authentication (Login & Registration)

✅ Real-time webcam video processing

✅ Multi-face tracking

✅ Attentiveness classification:

Attentive

Looking Down

Looking Away

Face Covered

Sleepy

✅ Interactive analytics dashboard

✅ Student-wise attentiveness tracking

✅ Timetable management

✅ Automated email report generation

✅ Database logging with timestamps

⚙️ Setup & Installation
1️⃣ Install Dependencies
pip install -r requirements.txt

2️⃣ Create Student Dataset
python create_dataset.py


Captures and stores facial images of students.

3️⃣ Generate Face Encodings
python encode_faces.py


Required before running the main application.

4️⃣ Run the Application
python app.py

5️⃣ Access the Web Interface

Open your browser and navigate to:

http://localhost:5000

🗃️ Database Models

User
Stores teacher and administrator account details.

AttentivenessLog
Stores student attentiveness status with timestamps.

Timetable
Stores subject schedules and faculty information.

🖼️ Screenshots

(Add screenshots here once available)

![Login Page](screenshots/login.png)
![Live Monitoring](screenshots/live_monitoring.png)
![Dashboard](screenshots/dashboard.png)
![Attentiveness Report](screenshots/report.png)

🎯 Use Cases

Smart classroom monitoring

Student engagement analysis

Academic performance insights

Educational analytics projects

AI-powered education systems

📄 License

This project is intended for educational and research purposes.
