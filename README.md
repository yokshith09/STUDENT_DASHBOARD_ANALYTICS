# 🎓 Student Performance Tracker

A **Flask + SQLite web application** to manage students, track grades, calculate averages, and generate performance reports.  
This project provides a modern **Bootstrap-based dashboard** for managing student data with features like adding students, assigning grades, class averages, toppers, and data backup.

---

## ✨ Features
- 📊 **Dashboard** – Quick stats on students, grades, and class average.  
- 👩‍🎓 **Manage Students** – Add, list, and view individual student profiles with their grades.  
- 📝 **Grade Management** – Assign grades for different subjects.  
- 📈 **Reports** – View per-student averages and class averages by subject.  
- 🏆 **Topper** – Find the highest scorer in a subject.  
- 💾 **Backup & Restore** – Export all student data to a file and re-import it later.  
- 🎨 **Modern UI** – Built with Bootstrap 5 & responsive sidebar layout.  

---

## 🛠️ Tech Stack
- **Backend:** Python (Flask), SQLAlchemy ORM  
- **Database:** SQLite  
- **Frontend:** HTML, Jinja2, Bootstrap 5, Bootstrap Icons  
- **Other:** Flash messages, file-based backup  

---

## 🚀 Getting Started

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

