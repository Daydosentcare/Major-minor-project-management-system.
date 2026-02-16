JEC Project Management System
A dynamic, client-side web application designed for Jabalpur Engineering College to facilitate the submission, tracking, and evaluation of Major and Minor projects. Built as a Single Page Application (SPA) for a hackathon, it simulates a full-stack project lifecycle without requiring a dedicated backend server.

🌟 Features
Role-Based Access Control:
Separate dashboards for Students and Faculty (Prof. Rajiv Dixit).
Students can submit projects, edit details, and track status.
Faculty can review projects, leave feedback, and assign grades.
Intelligent Workflow:
Auto-Status Shifting: When a faculty member clicks "Review" on a "New" project, it automatically moves to the "Unreviewed" section.
Auto-Completion: Upon grading and submission, the project is finalized in the "Reviewed" section, and the review button is hidden.
Evaluation System:
Standardized 1-10 Grading Scale.
Feedback Module: Allows for detailed comments that students can view in their "Status" section.
Data Management:
Persistent Storage: Uses browser localStorage to save projects, grades, and comments.
Demo Data: Pre-seeded with 11 realistic projects (including Team and Army personnel submissions).
ID Generation: Army personnel utilize the format 0201AI2510XX.
User Experience:
Dark Mode: Toggle switch for comfortable viewing.
Responsive Design: Fully functional on mobile and desktop.
Toast Notifications: Non-intrusive alerts for actions (Login, Submission, Grading).
🚀 Technology Stack
Frontend: HTML5
Styling: CSS3 (CSS Variables for theming, Flexbox/Grid layouts)
Logic: Vanilla JavaScript (ES6+)
Storage: Browser localStorage
No Frameworks: Pure JS implementation for maximum speed and portability.
📋 Usage
Prerequisites
Just a modern web browser. No installation required.

Accessing the System
Students:
User ID: 0201AI251099
Password: 123456
Faculty:
User ID: TEACHER1
Password: 123456
How to Run
Clone the repository.
Open index.html in your browser.
The system will auto-load demo data. To reset, clear your browser cache or refresh the page.
📸 Demo Projects Included
The system comes pre-loaded with 11 projects to demonstrate functionality across different statuses:

New Section (4): Drone Surveillance, Cyber Security Audit, AI Chatbot, Supply Chain Blockchain.
Unreviewed Section (6): IoT Home Automation (Team), Solar Tracker, Smart Agriculture, Hospital Management, Traffic Sign Recognition, Cloud Computing.
Reviewed (1): Blockchain Voting System (Grade: 9/10).
📜 Project Context
This tool was developed to solve the problem of fragmented project tracking in academic settings. It allows a centralized view for faculty (specifically Prof. Rajiv Dixit) to monitor the progress of multiple cohorts simultaneously, including submissions from student teams and army personnel.

👥 Credits
Developed for JEC Hackathon.

Student Lead: Mohit Sharma
Team Members: Harbajan Singh, Santosh Mahadik
Mentor: Prof. Rajiv Dixit
📄 License
MIT License. Feel free to use this for educational purposes.
