# Django To-Do App

A simple To-Do app built using Django, designed to help you manage your tasks efficiently. Users can create, view, update, and delete tasks with ease.

## Features

- Add new tasks with a title and description.
- Mark tasks as completed or pending.
- Update or delete existing tasks.
- Responsive design for mobile and desktop devices.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- Python 3.x
- Django 4.x
- Virtualenv (optional but recommended)

### Installation

```bash
#!/bin/bash

# Clone the project
git clone https://github.com/nabinupreti/django-todo-app.git

# Navigate to the project directory
cd django-todo-app

# Set up a virtual environment
python3 -m venv venv
source venv/bin/activate  # Linux/macOS
# OR for Windows
# venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create a superuser
python manage.py createsuperuser

# Start the Django development server
python manage.py runserver
```

## Contributing

Feel free to submit a pull request or open an issue if you want to contribute to this project.
