# Smart Attendance System
## 📋 Overview
The Smart Attendance System is a project designed to automate the process of attendance tracking in classrooms or workplaces. It uses facial recognition technology to identify and mark attendance of individuals automatically, making the process efficient, reliable, and user-friendly.

## 🚀 Features
- Facial Recognition: Automatically identifies and records attendance using facial recognition technology.
- Real-Time Detection: Captures attendance in real-time as individuals enter a designated area.
- User Management: Admins can add, update, or remove registered users.
- Attendance Reports: Generates detailed reports of attendance records that can be exported for analysis.

## 🛠️ Technology Stack
- Backend: Python (Django)
- Frontend: HTML, CSS, JavaScript
- Database: SQLite/MySQL
### Libraries:
- OpenCV: For image processing and face recognition.
- Numpy: For numerical operations.
- Pillow: For image handling.
- PyWin32: Windows-specific utility (optional, for Windows users).

## 📦 Installation
Clone the repository:

bash
git clone https://github.com/AmritaKaur-08/Smmart-Attendance-System.git
cd Smart-Attendance-System
Install dependencies:

bash
pip install -r requirements.txt
Setup database:

bash
python manage.py makemigrations
python manage.py migrate
Run the application:

bash
python manage.py runserver
Access the application: Open your browser and go to http://localhost:8000.
