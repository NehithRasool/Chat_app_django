# Django Chat Application

A simple chat application built with Django that supports user authentication, real-time messaging using WebSocket, and chat history.

## Features

1. User sign-up and login functionality.
2. Collapsible left menu to display all registered users.
3. Users can select and initiate chats with other registered users.
4. Store user data and chat messages in the database.
5. Retrieve and display old chat messages for users.
6. Real-time chat functionality using WebSocket.
7. A user-friendly chat interface.

---

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Python** (Version 3.8 or higher)
- **Django** (Version 4.0 or higher)
- **Node.js and npm** (for handling frontend dependencies, if any)
- **Redis** (for WebSocket and Django Channels, if used)
- **Git** (optional but recommended)

---

## Setup and Installation

1. **Clone the Repository**
   

   ```bash
   git clone https://github.com/your-repo/django-chat-app.git
   cd django-chat-app

2. **Create a Virtual Environment**
   

   ```bash
   python -m venv env
   source env/bin/activate    


3.**Install Dependencies**

    ```bash
    pip install -r requirements.txt
4.**Setup the Database**
  -Apply migrations to set up the database schema:
  
        ```bash
        python manage.py makemigrations
        python manage.py migrate
5.**Create a Superuser**
  -Create an admin account for managing users and messages:

      ```bash
      python manage.py createsuperuser
6.**Start the Development Server**

    ```bash
    python manage.py runserver
