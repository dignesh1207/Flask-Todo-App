# 📝 Flask Todo App

A simple and clean Todo List web application built with **Flask** and **SQLite**. Add tasks, set due dates, mark them as complete, and delete them — all persisted in a local database.

---

## 🚀 Features

- ✅ Add tasks with an optional due date
- ☑️ Toggle tasks as complete / incomplete
- 🗑️ Delete tasks
- 💾 Data persisted with SQLite via SQLAlchemy
- 🎨 Clean, minimal UI with pure HTML & CSS

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python, Flask |
| Database | SQLite + Flask-SQLAlchemy |
| Frontend | HTML, CSS (Jinja2 templates) |

---

## 📁 Project Structure

```
flask-todo-app/
├── app.py               # Main Flask application
├── templates/
│   └── index.html       # Frontend template
├── instance/
│   └── site.db          # SQLite database (auto-generated)
├── venv/                # Virtual environment (not committed)
└── README.md
```

---

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Create and activate a virtual environment
```bash
python3 -m virtualenv venv
source venv/bin/activate        # macOS/Linux
# venv\Scripts\activate         # Windows
```

### 3. Install dependencies
```bash
pip install flask flask-sqlalchemy
```

### 4. Run the app
```bash
python app.py
```

### 5. Open in browser
```
http://127.0.0.1:5000
```

The database (`instance/site.db`) will be created automatically on first run.

---

## 📸 Screenshots

> _Add a screenshot of your app here once it's live!_
> `![App Screenshot](screenshots/preview.png)`

---

## 📌 Notes

- This project was built as a learning exercise following along with [CodeWithHarry](https://www.youtube.com/@CodeWithHarry)
- Not intended for production use — this is a development server

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
