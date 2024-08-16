
# User CRUD Service

This repository contains a CRUD (Create, Read, Update, Delete) service for managing `User` data, built using Python and Django. The service includes functionality to create, retrieve, update, and delete users.

## Project Structure

- **myproject/**: Main Django project folder.
- **myapp/**: Django app containing the `User` model and views for CRUD operations.
- **templates/**: HTML templates for rendering the UI.

## User Model

The `User` model has the following fields:

- `username`: A string representing the username.
- `password`: A string representing the password.
- `active`: A boolean indicating whether the user is active.

## Setup Instructions

Follow these steps to set up and run the project locally:

### Prerequisites

- Python 3.x
- Django 3.x
- Git

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/adnanshafiwork/python_crud.git
   cd python_crud
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Apply database migrations:**

   ```bash
   python manage.py migrate
   ```

4. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

5. **Access the application:**

   Open your browser and go to `http://127.0.0.1:8000/` to view the user CRUD interface.
