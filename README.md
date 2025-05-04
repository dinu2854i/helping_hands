# Helping Hands 🤝

A Django-based platform to connect people in need with volunteers offering help.

## Features

- User registration and login
- Post requests for help
- Volunteer management
- Admin dashboard

## Tech Stack

- Python 3.13
- Django
- MySQL
- Bootstrap (or Tailwind)
- Render / Heroku (for deployment)

## Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/helping-hands.git
   cd helping-hands
   ```

2. Create and activate a virtual environment:
   ```bash
   python3.13 -m venv env
   source env/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Update `.env` or `settings.py` with your MySQL credentials.

5. Run migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

6. Start server:
   ```bash
   python manage.py runserver
   ```
