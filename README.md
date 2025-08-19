# 📝 TO-DO-LIST-Django

A **Full Stack To-Do List Web Application** built using **Django, HTML, CSS** with user authentication.  
This project allows users to register, login, manage their tasks (create, edit, delete), and logout securely.

---

## 🚀 Features
- ✅ User Registration & Login (Authentication)
- ✅ Add, Edit, and Delete Tasks
- ✅ Mark tasks as complete/incomplete
- ✅ Organized Templates (Base, Nav, Home, Edit, Login/Register, etc.)
- ✅ Static Files (CSS, Images)
- ✅ SQLite database (default Django DB)

---

## 🛠️ Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS
- **Database:** SQLite3
- **Authentication:** Django Auth System

---

## 📂 Project Structure
TODO_final/
│── base/ # Core app (Task management)
│ ├── templates/ # Task templates (home, edit, etc.)
│── authen/ # Authentication app (login, register, logout)
│ ├── templates/ # Auth templates
│── static/ # CSS, images
│── db.sqlite3 # Database (excluded in git)
│── manage.py # Django project manager


---

## ⚡ Setup Instructions

   ```bash
   git clone https://github.com/githuanand/TO-DO-LIST-Django.git
   cd TO-DO-LIST-Django
   setup_instructions:

   create_and_activate_virtual_environment:
    windows: "venv\\Scripts\\activate"
    mac_linux: "source venv/bin/activate"
    command: "python -m venv venv"

   install_dependencies:
    command: "pip install -r requirements.txt"

   run_migrations:
    command: "python manage.py migrate"

   create_superuser:
    command: "python manage.py createsuperuser"

   start_development_server:
    command: "python manage.py runserver"
    open_in_browser: "http://127.0.0.1:8000/"

