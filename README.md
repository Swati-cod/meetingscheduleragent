Meeting Scheduler Agent with Data Analysis
Live Application URL
https://meetingscheduleragent.onrender.com
1. Project Overview
The Meeting Scheduler Agent is a web-based intelligent scheduling system developed using Flask. The application automatically schedules meetings based on participant availability, stores meeting records in a database, and provides a separate data analysis page to display statistical insights.
This project demonstrates intelligent agent principles, database integration, backend development, and cloud deployment.
2. Objectives
The main objectives of this project are:
To implement an intelligent scheduling mechanism.
To store and manage meeting records using a relational database.
To analyze stored data and generate meaningful statistics.
To deploy a backend-based web application in the cloud.
3. Features
Automatic meeting scheduling based on common availability.
Persistent meeting storage using SQLite.
Dedicated Data Analysis page.
Displays:
Total number of meetings.
Most frequently scheduled time slot.
Number of meetings per participant.
Cloud deployment using Render.
Proper Flask project structure.
4. Technology Stack
Backend
Python
Flask
Frontend
HTML
CSS
Database
SQLite
Deployment
Render (Web Service)
Version Control
GitHub
5. Project Structure
meeting-scheduler/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   ├── index.html
│   └── analysis.html
│
└── static/
    └── style.css
6. System Architecture
The application follows a basic intelligent agent model:
Perception
The system reads predefined participant availability.
Decision Making
It computes the intersection of available time slots.
Action
It schedules a meeting automatically if a common slot exists.
Learning and Analysis
It uses stored meeting records to compute statistics on the analysis page.
7. Database Information
The application uses SQLite as its database system.
Database File
meetings.db
Table Structure
Table Name: meetings
Columns:
id (Primary Key, Auto Increment)
participants (Text)
time_slot (Text)
The database file is automatically created during runtime.
8. screenshot of output
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/966ea063-6f00-4c32-a2be-cc033ef8b04e" />
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/d483fcea-bbac-4a45-9e44-49804ada14f1" />

