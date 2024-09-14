# Simple Blog Application

## Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd mysite
   
Blog application made with Django
Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate

Install dependencies:
pip install -r requirements.txt

Apply migrations:
python manage.py migrate

Create a superuser:
python manage.py createsuperuser

Run the development server:
python manage.py runserver

Functionality
Users can read, create, update, and delete blog posts.
User authentication for creating and managing posts.
Admin panel for managing all posts.
