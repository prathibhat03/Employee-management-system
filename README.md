# Employee-management-system
The Employee Management System is a web-based application built using Django, JavaScript, HTML, CSS, and MySQL. This project manages their employee data efficiently. It consists of two main applications: empapp1 for employee-related operations and empapp2 for administrative functions.

=>PROJECT STRUCTURE

Employee_Management_System

=>Employee_Management_System

init.py

asgi.py

settings.py

urls.py

wsgi.py

=>empapp1

init.py

admin.py

apps.py

forms.py

models.py

tests.py

urls.py

views.py

=>empapp2

init.py

admin.py

apps.py

forms.py

models.py

tests.py

urls.py

views.py

static

empapp1
css
images
js
empapp1
css
images
js
templates
empapp1
all templates files

empapp2
all twmplates files
manage.py

=>FEATURES

User registration and login system

Employee profile management

Employee education details management

Employee experience details management

Admin login for staff or superusers

Admin can view, edit, and delete employee data

Admin can change their password

User-friendly interface

=>INSTALLATION

To run this project on your local machine, follow these steps:

Clone the repository: git clone https://github.com/your-username/employee-management-system.git

Navigate to the project directory: cd employee-management-system

Create a virtual environment (recommended): python -m venv venv

Activate the virtual environment:

On Windows: - venv\Scripts\activate
Install the project dependencies: pip install -r requirements.txt

Create and configure the MySQL database:

Create a MySQL database named "Employee_Management_System".
Update the database settings in Employee_Management_System/settings.py with your MySQL credentials.
Apply migrations to create database tables: python manage.py migrate

Create a superuser account: python manage.py createsuperuser

Run the development server: python manage.py runserver Access the web application in your browser at http://localhost:8000.

Usage
Visit the application in your browser and create a user account or log in as an admin.
Users can manage their employee profiles, education, and experience details.
Admins can log in to access administrative functions such as viewing, editing, and deleting employee data.
Admins can also change their password.
Access the web application in your browser at http://localhost:8000. it will gives this interface.
