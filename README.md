# Placement-Portal---Placement-Portal-Student-Admin-Management-System
A full-stack web application designed to streamline the campus placement process. This portal enables students to register, upload resumes, receive AI-based job recommendations, and apply for jobs. Admins can post job opportunities, track student applications, and manage recruitment data. Developed using Flask, MySQL, HTML/CSS, and JavaScript.

## 📌 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup Instructions](#setup-instructions)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Contributors](#contributors)
- [License](#license)

---

## ✅ Features

### 👨‍🎓 Student Module
- Resume upload with PDF parsing using NLP
- Automatic profile creation (Name, Education, Skills, etc.)
- AI-based job recommendations using Sentence-BERT
- Track application history and job statuses

### 🧑‍💼 Admin Module
- Post new job opportunities and manage listings
- View student applications for each job
- Monitor real-time statistics of student engagement

---

## ⚙️ Tech Stack

| Frontend | Backend | Database | AI/NLP |
|----------|---------|----------|--------|
| HTML5, CSS3, JavaScript | Flask (Python) | MySQL | PyMuPDF, spaCy, Sentence-BERT |

---

## 🚀 Setup Instructions

### 1. Clone the Repository

git clone https://github.com/your-username/placement-portal.git
cd placement-portal

### 2. Create and Activate Virtual Environment

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

### 3. Install Required Packages
pip install flask
pip install flask-cors
pip install mysql-connector-python
pip install PyMuPDF
pip install spacy
pip install sentence-transformers
pip install pandas
python -m spacy download en_core_web_sm

### 4 Configure the MySQL Database

Create a database called placement_portal.

Import the provided schema from /db/schema.sql.

### 5. Run the App

python app.py



### Project Structure

placement-portal/
├── static/                  # CSS, JS, and assets
├── templates/               # HTML templates (Jinja2)
├── resume_parser/           # Resume parsing logic
├── app.py                   # Flask app and API routes
├── db_config.py             # DB connection config
├── requirements.txt         # Python dependencies
└── README.md



```bash
git clone https://github.com/your-username/placement-portal.git
cd placement-portal

### 2. Clone the Repository
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


pip install flask
pip install flask-cors
pip install mysql-connector-python
pip install PyMuPDF
pip install spacy
pip install sentence-transformers
pip install pandas
python -m spacy download en_core_web_sm


4. Configure the MySQL Database
Create a database called placement_portal.

Import the provided schema from /db/schema.sql.

python app.py


