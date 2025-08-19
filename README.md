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
1. Clone the repository:
   ```bash
   git clone https://github.com/githuanand/TO-DO-LIST-Django.git
   cd TO-DO-LIST-Django
2. Create & activate virtual environment:

python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate # On Mac/Linux


3. Install dependencies:

  pip install -r requirements.txt


4. Run migrations:

  python manage.py migrate


5. Create superuser (for admin access):

  python manage.py createsuperuser


6. Start development server:

  python manage.py runserver


7. Now open http://127.0.0.1:8000/
   in your browser
