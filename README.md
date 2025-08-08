# Django Banking App 💰

A secure and simple Django-based banking system for user signup, login, deposit, withdrawal, and account summaries.

## 🚀 Features
- JWT-based authentication
- Salary deposit with month/year tracking
- Tax deductions (18%)
- Financial summaries per employee

## 🛠️ Tech Stack
- Django
- SQLite
- Python
- Bootstrap (optional)

## ⚙️ Setup Instructions

```bash
git clone https://github.com/diksharana007/django-banking-app.git
cd django-banking-app
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
