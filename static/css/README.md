# 📝 Task Manager (Flask App)

A simple **Task Manager web application** built using **Flask** and **SQLite**.
Users can add, update, and delete tasks.

---

## 🚀 Features

* Add new tasks
* View all tasks
* Update existing tasks
* Delete tasks
* Stores data using SQLite database

---

## 🛠️ Tech Stack

* Python (Flask)
* HTML (Jinja Templates)
* CSS
* SQLite (Flask-SQLAlchemy)

---

## 📂 Project Structure

```
myapp/
│
├── app.py
├── static/
│   └── css/
│       └── main.css
├── templates/
│   ├── base.html
│   ├── index.html
│   └── update.html
└── instance/
    └── test.db
```

---

## ▶️ How to Run

1. Clone the repository
2. Create virtual environment

```
python -m venv env
env\Scripts\activate
```

3. Install dependencies

```
pip install flask flask-sqlalchemy
```

4. Run the app

```
python app.py
```

5. Open browser:

```
http://127.0.0.1:5000
```

---

## 📌 Note

This is a beginner-level project to understand Flask, templates, and database integration.

---
