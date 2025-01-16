Django Chat Application

A real-time chat application built with Django.

Setup and Installation

Follow the steps below to set up and run the application locally.

Clone the Repository git clone
https://github.com/your-repo/django-chat-app.git cd django-chat-app

Create a Virtual Environment python -m venv env source env/bin/activate
\# On Windows: env\\Scripts\\activate

Install Dependencies pip install -r requirements.txt

Setup the Database Apply migrations to set up the database schema:

python manage.py makemigrations python manage.py migrate

Create a Superuser Create an admin account for managing users and
messages:

python manage.py createsuperuser

Start the Development Server Run the application locally:

python manage.py runserver

Access the app at: http://127.0.0.1:8000

Features

Real-time messaging

User authentication

Admin interface for managing users and messages

Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch for your feature or bug fix:

git checkout -b feature-name

Commit your changes:

git commit -m \"Add your message here\"

Push to your fork:

git push origin feature-name

Create a pull request.
