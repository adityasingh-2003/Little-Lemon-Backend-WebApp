# 🍋 Little Lemon Web App

A full-stack Django web application developed as part of the **Meta Back-End Developer Capstone Project** on Coursera. This app simulates a reservation system for the fictional restaurant **Little Lemon**, showcasing back-end development skills including Django views, models, templates, forms, authentication, and deployment.

## 🚀 Project Features

- ✅ User registration & authentication
- 📅 Table reservation system
- 📬 Contact form with email notifications
- 📊 Admin dashboard for managing bookings
- 🎨 Responsive UI using Bootstrap
- 🗃️ SQLite/PostgreSQL database integration

## 🛠️ Tech Stack

- **Framework:** Django (Python)
- **Frontend:** HTML5, CSS3, Bootstrap
- **Database:** SQLite (development) / PostgreSQL (production-ready)
- **Deployment:** [Optional: Add deployment service if applicable, e.g., Vercel, Heroku, or Render]

## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/YOUR_USERNAME/little-lemon-webapp.git
   cd little-lemon-webapp
Create a virtual environment:

bash
Copy
Edit
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Apply migrations:

bash
Copy
Edit
python manage.py migrate
Run the server:

bash
Copy
Edit
python manage.py runserver
Access the app: Open your browser and go to http://127.0.0.1:8000/

🧪 Testing
Run unit tests using Django's built-in testing framework:

bash
Copy
Edit
python manage.py test
📁 Project Structure
bash
Copy
Edit
little-lemon/
├── reservations/         # Main app for booking
├── users/                # Custom user handling
├── templates/            # HTML templates
├── static/               # CSS and JS
├── manage.py
└── requirements.txt
👨‍💻 Author
Your Name – @yourgithub

Capstone Project for Meta Back-End Developer Program – Coursera
