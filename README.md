# Simple Blog Application

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone <repository_url>
    cd mysite
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv env
    source # On Windows use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run migrations:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. Run the development server:
    ```bash
    python manage.py runserver
    ```

## Functionality

- Users can sign up, log in, and log out.
- Authenticated users can create, edit, and delete their own blog posts.
- All blog posts are listed on the home page in reverse chronological order.
- Admins can manage all blog posts through the Django admin panel.
