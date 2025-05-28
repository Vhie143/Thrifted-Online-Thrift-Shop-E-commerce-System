# 🛍️ Thrifted Online Thrift Shop E-commerce System

A Django web application for managing an online thrift shop, allowing users to browse, purchase, and manage second-hand items.

---

## Pre-requisites

Ensure the following are installed:

- Python (version 3.8+)
- pip (Python package installer)
- Virtualenv (recommended)
- Git (if cloning from a repository)
- Database (e.g., SQLite is default; MySQL/PostgreSQL may require additional setup)

---

## Steps to Run the Django App

### 1. Clone or Download the Project
    git clone https://github.com/yourusername/Thrifted-Online-Thrift-Shop-E-commerce-System.git (or download as zip)
    cd Thrifted-Online-Thrift-Shop-E-commerce-System

### 2. Create and Activate a Virtual Environment (Recommended)
    - ```python -m venv venv```
    - ```venv\Scripts\activate```

### 3.  Install Required Dependencies
    - ```pip install -r requirements.txt```
    - ```pip install django```

### 4.  Configure Database (Optional)
    Check settings.py in the main Django app folder for DATABASES config.
    -```If using SQLite (default), no action is needed.```
    -```If using MySQL/PostgreSQL, configure username, password, and engine.```

### 5.  Run Migrations
    - ```python manage.py makemigrations```
    - ```python manage.py migrate```

### 6.   Create Superuser (Admin Account)
    - ```python manage.py createsuperuser```

### 7.   Run the Development Server
    - ```python manage.py runserver```

MEMBERS:
AUCILLA, CRISELDA VHIE O.
ROBIS, BRENT KRISTIAN L.
SANTOS, VANNAH MAIE R.