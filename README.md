# Django Chat Application

A real-time chat application built with Django and WebSocket. This application allows users to sign up, log in, and chat with other registered users in real-time.

## Features

- User Sign-up and Login functionality
- Collapsible left menu displaying all registered users
- Real-time messaging using WebSocket
- Stores user data and chat messages in the database
- Retrieve and display old messages in the chat interface
- User-friendly and functional chat interface

---

## Prerequisites

Before running the project, ensure you have the following installed:

1. **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2. **Django Framework**: Installed using `pip`
3. **Channels for WebSocket**: Installed using `pip`
4. **Visual Studio Code (VS Code)**: [Download VS Code](https://code.visualstudio.com/)

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/<your-username>/django-chat-app.git
cd django-chat-app
Set Up Virtual Environment
Create a virtual environment:
bash
Copy
Edit
python -m venv venv
Activate the virtual environment:

On Windows:
bash
Copy
Edit
venv\Scripts\activate
On macOS/Linux:
bash
Copy
Edit
source venv/bin/activate
Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
Apply Database Migrations
bash
Copy
Edit
python manage.py migrate
Create a Superuser
Create a superuser account to access the Django admin panel:

bash
Copy
Edit
python manage.py createsuperuser
Follow the prompts to set up a username, email, and password.

Run the Development Server
bash
Copy
Edit
python manage.py runserver
Access the application in your browser at:
http://127.0.0.1:8000
