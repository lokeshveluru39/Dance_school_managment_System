# Dance School Management System (ERP)
This project is a full-stack Django-based ERP system for managing a dance school. It provides features for student enrollment, class scheduling, attendance tracking, instructor management, fee management, and reporting.

## Prerequisites

- Python 3.x installed
- PostgreSQL or SQLite (default) installed
- pip (Python package manager)
- Virtual environment (recommended)

## Installation Steps

# Clone the Repository:
    git clone https://github.com/your-username/dance-school-management.git
    cd dance-school-management
# Create and Activate Virtual Environment:
    python -m venv venv
# On Windows:
    venv\Scripts\activate
# On macOS/Linux:
    source venv/bin/activate

##  Install Dependencies:
    pip install -r requirements.txt

## Configure Environment Variables:
Create a .env file in the project root and add the necessary configurations such as database credentials, secret keys, etc.

# Apply Migrations:
    python manage.py migrate
# Create a Superuser (for Admin Access):
    python manage.py createsuperuser

## Follow the prompts to set up an admin account.
# Run the Development Server:
    python manage.py runserver

-The application will be accessible at http://127.0.0.1:8000/.
-Running the Project

# Navigate to the Project Directory:
    cd dance-school-management

# Run the Application:
    python manage.py runserver

Access Admin Panel:
-Visit http://127.0.0.1:8000/admin/ and log in using the superuser credentials created earlier.
<br><br>

Common Issues and Solutions:
* Database Connection Errors:
Ensure the correct database credentials are set in .env.
Check if the database service is running.
<br><br>

Static Files Not Loading:
* Run python manage.py collectstatic.
Ensure DEBUG = False in production and proper static file settings are configured.
<br><br>

Module Not Found Errors:
* Ensure dependencies are installed with pip install -r requirements.txt.
Activate the virtual environment before running commands.
<br><br>

Features:<br>
* Student Enrollment: Manage student records and enrollments.<br>
* Class Scheduling: Assign students to classes based on level and availability.<br>
* Attendance Tracking: Monitor student attendance and performance.<br>
* Instructor Management: Maintain instructor details and schedules.<br>
* Fee Management: Handle fee payments, invoices, and due tracking.<br>
