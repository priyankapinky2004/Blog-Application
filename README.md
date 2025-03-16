📝 Blog Application

A simple Django-based Blog Application where users can create, read, update, and delete blog posts.

📌 Features

🅲️ User Authentication (Login, Logout, Register)
📰 Create, Read, Update, Delete (CRUD) Blogs
🏷️ Category & Tagging System
🖼️ Image Upload Support (Pillow Library)
💃 Database Management using SQL
🌍 Time Zone Support

🚀 Installation Guide

1⃣ Clone the Repository

git clone https://github.com/priyankapinky2004/Blog-Application.git
cd Blog-Application

2⃣ Create and Activate a Virtual Environment

# Create virtual environment
py -m venv env  

# Activate it (Windows)
.\env\Scripts\activate  

3⃣ Install Dependencies

pip install django pillow

4⃣ Database Migrations

python manage.py makemigrations  
python manage.py migrate  

5⃣ Create a Superuser (For Admin Access)

python manage.py createsuperuser  

Follow the prompts to set up a username, email, and password.

6⃣ Run the Development Server

python manage.py runserver  

Access the app at http://127.0.0.1:8000/


🛠️ Tech Stack
Backend: Django
Database: SQLite
Frontend: HTML, CSS, Bootstrap
Libraries Used: Pillow, sqlparse, tzdata

👥 Contribution:
Feel free to contribute! Fork the repository and submit a pull request.
