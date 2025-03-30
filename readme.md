#Quiz App

##📌 Overview

This is a Flask-based Quiz Application that allows users to:

Register and log in as a user or admin.

Create quizzes with Single-choice questions.

Answer quizzes and submit responses.

View quiz results.

##🚀 Features

User Registration & Login 

Admin Dashboard (Create and manage quizzes)

Quiz Attempt & Submission

Question Status Update

Database-backed storage (SQLite by default)

RESTful API Design

##🛠️ Installation & Setup

###1️⃣ Clone the Repository

git clone https://github.com/23f2002880/quiz_master_23f2002880.git
cd quiz-app  (enter to the directory)

###2️⃣ Create & Activate a Virtual Environment (ignore if running your own env)

On Windows <br>
python -m venv venv
Set-ExecutionPolicy Unrestricted -Scope Process  (if aliasing issue)
venv\Scripts\activate

On macOS/Linux <br>
python3 -m venv venv
source venv/bin/activate

###3️⃣ Install Dependencies

pip install flask flask_sqlalchemy flask_migrate flask_restful sqlalchemy Werkzeug

###4️⃣ Database is already set up.
Admin Credentials: 
username : admin
password : admin123

Dummy user credentilas:

username : user1
password : password

###5️⃣ Run the Application

python app.py

The server will start at: http://127.0.0.1:5000
