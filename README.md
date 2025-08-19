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





Project:
  name: "TO-DO-LIST-Django"
  description: "Full Stack Django To-Do List app with user authentication"
  author: "githuanand"
  license: "MIT"

Features:
  - "User Registration & Login (Authentication)"
  - "Add, Edit, and Delete Tasks"
  - "Mark tasks as complete/incomplete"
  - "Organized Templates (Base, Nav, Home, Edit, Login/Register, etc.)"
  - "Static Files (CSS, Images)"
  - "SQLite database (default Django DB)"
    

Tech_stack:
  backend: "Django (Python)"
  frontend: "HTML, CSS"
  database: "SQLite3"
  authentication: "Django Auth System"

  

Project_structure:
  root:
    - manage.py
    - db.sqlite3 (excluded in git)
    - requirements.txt
    - README.md
    - .gitignore
    - TODO_final/

    
  TODO_final:
    - base/  # Core app (Task management)
    - authen/  # Authentication app
    - static/  # CSS, Images
    - templates/  # Shared HTML templates


Setup_instructions:
  create_and_activate_virtual_environment:
    command: "python -m venv venv"
    windows: "venv\\Scripts\\activate"
    mac_linux: "source venv/bin/activate"


  install_dependencies:
    command: "pip install -r requirements.txt"


  run_migrations:
    command: "python manage.py migrate"

  create_superuser:
    command: "python manage.py createsuperuser"

  start_development_server:
    command: "python manage.py runserver"
    open_in_browser: "http://127.0.0.1:8000/"



git_setup:
  gitignore:
    content: |
      # Python
      *.pyc
      __pycache__/
      *.pyo
      *.pyd



      # Django
      db.sqlite3
      media/
      staticfiles/


      # Virtual Environment
      venv/
      .env


      # VS Code
      .vscode/
 
  requirements:
    generate: "pip freeze > requirements.txt"
    push:
      - "git add requirements.txt"
      - "git commit -m 'Added requirements.txt'"
      - "git push origin main"


license:
  type: "MIT"
  content: |
    MIT License


    Copyright (c) 2025 githuanand

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the 'Software'), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.



Contribution:
  steps:
    - "Fork the repository"
    - "Create a new branch (git checkout -b feature-branch)"
    - "Make your changes"
    - "Commit (git commit -m 'Added new feature')"
    - "Push (git push origin feature-branch)"
    - "Open a Pull Request"



screenshots:
  - "Home Page: <img width="1365" height="612" alt="image" src="https://github.com/user-attachments/assets/8b67d332-e402-4fc0-8bd7-09598200afe6" />

  - "Login Page: <img width="1332" height="611" alt="image" src="https://github.com/user-attachments/assets/4c120b31-9795-4584-9eb6-3cf8438a42dc" />

  - "Register Page: <img width="1365" height="605" alt="image" src="https://github.com/user-attachments/assets/872c62f5-30a5-4373-a074-4c2e820bd1d7" />



