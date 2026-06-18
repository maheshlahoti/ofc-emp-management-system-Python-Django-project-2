# Office Employee Management System

A web-based Employee Management System developed using **Python** and **Django** that enables organizations to efficiently manage employee records, departments, and roles. The application provides a centralized platform for performing employee-related operations through a simple and intuitive interface.

## Features

* Add new employees
* View all employee records
* Update employee information
* Delete employee records
* Manage departments and job roles
* Search and filter employees
* Django Admin Panel integration
* Database-driven architecture
* Responsive and user-friendly interface

## Tech Stack

### Backend

* Python
* Django
* Django ORM

### Database

* SQLite

### Frontend

* HTML
* CSS
* Bootstrap

### Tools

* Git
* GitHub
* VS Code

## System Architecture

The application follows Django's MVT (Model-View-Template) architecture:

* **Models:** Handle database operations and business logic.
* **Views:** Process user requests and interact with models.
* **Templates:** Render dynamic content for users.

## Database Models

### Employee

* First Name
* Last Name
* Department
* Role
* Salary
* Bonus
* Phone Number
* Hire Date


## Installation

### Clone Repository

```bash
git clone https://github.com/<your-github-maheshlahoti>/office-employee-management-system.git
cd office-employee-management-system
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

```bash
# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create Superuser

```bash
python manage.py createsuperuser
```

### Run Server

```bash
python manage.py runserver
```

Visit:

```text
http://127.0.0.1:8000/
```

## Key Learning Outcomes

* Django Framework Fundamentals
* CRUD Operations
* Django ORM
* Database Management
* URL Routing
* Template Rendering
* Authentication Concepts
* Git & GitHub Workflow
* Backend Development Best Practices

## Future Enhancements

* REST API Development using Django REST Framework
* JWT Authentication
* Employee Attendance Management
* Leave Management System
* PostgreSQL Integration
* Docker Containerization
* Cloud Deployment (AWS)


