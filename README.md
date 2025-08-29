# 🎓 Student Performance Tracker

This is my **first project using Flask and SQLite** 🎉.  
I built it to learn how a backend framework (Flask) works with a database (SQLite) and how to combine them with HTML, Bootstrap, and Jinja2 templates to create a complete web application.  

The app helps to **manage students and their grades**, calculate averages, find toppers, and generate reports — all inside a simple but modern dashboard UI.  

---

## 🚀 What I Learned
- How to set up a Flask project and run a development server.  
- How to connect Flask with **SQLite** using **SQLAlchemy ORM**.  
- How to create models (`Student`, `Grade`) and define relationships.  
- How to use **Flask routes** to handle forms and render templates.  
- How to use **Jinja2 templates** with Bootstrap for a modern UI.  
- How to implement backup & restore with files.  

---

## ✨ Features
- 📊 **Dashboard** – Shows quick stats like total students, total grades, and class average.  
- 👩‍🎓 **Students** – Add new students, view student lists, and see their details.  
- 📝 **Grades** – Assign grades to students for different subjects.  
- 📈 **Reports** – Calculate averages per student and per subject.  
- 🏆 **Topper** – Find the highest scorer in a subject.  
- 💾 **Backup & Restore** – Export all student data into a file and re-import later.  
- 🎨 **Responsive Design** – Clean Bootstrap 5 interface.  

---

## 🛠️ Tech Stack
- **Backend:** Python (Flask)  
- **Database:** SQLite (via SQLAlchemy)  
- **Frontend:** Bootstrap 5 + Jinja2 templates  
- **Other:** Flask Flash messages, file-based backup  

---

## 📂 Project Structure



### 1️⃣ Clone the repo
```bash
git clone https://github.com/yourusername/student-tracker.git
cd student-tracker

2️⃣ Create virtual environment & install dependencies
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

pip install -r requirements.txt

3️⃣ Run the app
python app.py

