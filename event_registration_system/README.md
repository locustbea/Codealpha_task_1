# Event Registration System

## Overview
The Event Registration System is a web application that allows users to register for events, view event details, and manage their registrations. It is built using Django (Python) for the backend framework by Olalekan Onifade.

## Features
- User registration and authentication
- Event creation and management
- User registration for events
- View event details
- Manage event registrations

## Technologies Used
- Python
- Django
- SQLite (default database, can be replaced with PostgreSQL or MySQL)
- HTML/CSS for front-end

## Installation

### Prerequisites
- Python 3.8 or higher
- Django 4.0 or higher

### Steps
1. Clone the repository:
    ```sh
    git clone https://github.com/locustbea/event_registration_system.git
    cd event_registration_system
    ```

2. Set up a virtual environment and activate it:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```sh
    python manage.py migrate
    ```

5. Create a superuser for admin access:
    ```sh
    python manage.py createsuperuser
    ```

6. Run the server:
    ```sh
    python manage.py runserver
    ```

7. Open your browser and navigate to `http://127.0.0.1:8000/` to access the application.

## Directory Structure

event_registration_system/
├── event_registration_system/
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
├── events/
│ ├── migrations/
│ ├── templates/
│ │ └── events/
│ │ ├── event_detail.html
│ │ ├── event_list.html
│ │ ├── index.html
│ │ ├── registration_form.html
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── tests.py
│ ├── urls.py
│ ├── views.py
├── manage.py
└── requirements.txt

csharp


## Usage
1. Register and log in as a user.
2. Browse the list of events.
3. Register for an event.
4. View and manage your event registrations.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
