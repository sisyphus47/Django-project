# 🛍️ Django Shopping App

A fully functional e-commerce web application built with Django and Tailwind CSS, deployed live on [Railway](https://railway.app).

---

## 🚀 Live Demo

👉 [Visit the App](https://your-app-name.up.railway.app)

---

## 📦 Features

- 🔐 User Authentication (Signup/Login)
- 🛒 Item Listing with Images, Categories, Price
- 📬 Messaging between buyers and sellers
- 🔍 Search & Filter Items by Category or Keyword
- 👤 User Dashboard to manage listed items
- 📤 Upload Images via Forms
- 📦 Deployed on Railway with PostgreSQL

---

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: Tailwind CSS, HTML Templates
- **Database**: PostgreSQL (via Railway)
- **Hosting**: [Railway](https://railway.app)

---

## 🧰 Setup Instructions (Local Development)

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# 2. Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Apply migrations
python manage.py migrate

# 5. Create superuser (optional)
python manage.py createsuperuser

# 6. Run development server
python manage.py runserver
