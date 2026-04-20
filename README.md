# Django Blog App

A full-stack blog application built using Django. This project allows users to create, edit, and manage blog posts with authentication and a clean user interface.

---

## 🚀 Features

* User Authentication (Login / Signup / Logout)
* Create, Edit, Delete Blog Posts
* Responsive UI using HTML, CSS, Bootstrap
* Secure backend using Django
* Clean and modular project structure

---

## 🛠️ Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS, Bootstrap
* **Database:** SQLite (local development)
* **Version Control:** Git & GitHub

---

## 📂 Project Structure

```
blog-app/
│
├── manage.py
├── db.sqlite3 (ignored in Git)
├── requirements.txt
│
├── blog/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
│
└── static/
```

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/django-blog-app.git
cd django-blog-app
```

### 2. Create virtual environment

```
python -m venv venv
```

### 3. Activate environment

**Windows:**

```
.\venv\Scripts\Activate
```

**Mac/Linux:**

```
source venv/bin/activate
```

### 4. Install dependencies

```
pip install -r requirements.txt
```

### 5. Run migrations

```
python manage.py migrate
```

### 6. Start server

```
python manage.py runserver
```

---

## 🌐 Usage

Open in browser:

```
http://127.0.0.1:8000/
```

---

## 📌 Future Improvements

* Add comments system
* Like / save posts feature
* User profile dashboard
* Deployment (Render / Railway)

---

## 👨‍💻 Author

Sahil Sayyed
GitHub: https://github.com/Sahil-TRCAC

---
