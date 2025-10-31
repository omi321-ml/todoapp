# 🧮 Django Project

## 📖 Overview
This is a Django-based web application project.  
It includes database support using **SQLite**, and you can manage your site using Django’s powerful **admin interface**.

---

## 🎯 Objective
The main goal of this project is to demonstrate:
- Django project setup
- Database integration
- URL routing
- Admin management

---

## 🧰 Tools & Technologies
- **Python**
- **Django**
- **SQLite**
- **HTML / CSS**
- **VS Code**

---

## ⚙️ Installation & Setup

Follow these steps to run the project on your computer:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/your-repository-name.git
```

### 2️⃣ Navigate into the Project Folder
```bash
cd your-repository-name
```

### 3️⃣ Create a Virtual Environment
```bash
python -m venv venv
```
Activate it:
- On Windows:
  ```bash
  venv\Scripts\activate
  ```
- On Mac/Linux:
  ```bash
  source venv/bin/activate
  ```

### 4️⃣ Install Required Packages
```bash
pip install -r requirements.txt
```

### 5️⃣ Run Migrations
```bash
python manage.py migrate
```

### 6️⃣ Start the Server
```bash
python manage.py runserver
```

Then open your browser and visit:
👉 http://127.0.0.1:8000/

---

## 🧱 Project Structure
```
myproject/
│
├── manage.py
├── db.sqlite3
├── myapp/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
│
└── myproject/
    ├── settings.py
    ├── urls.py
    └── wsgi.py
```

---

## 📊 Database
The project uses **SQLite** by default (comes with Django).  
Database file: `db.sqlite3`
