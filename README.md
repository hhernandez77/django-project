# Task Management

This is a simple Task Management program that allows users to create, view, update, and delete tasks. This also includes user authentication for managing task securely.

## Features
### User Authentication
    * Authentication ensures that each user can manage only their task
    * Register an account and login to access the task management system.

### Task Management
    * Create a Task: Users can create tasks by providing a title, description and date.<>
    * View Task: Users can view a list of all their created task.
    * Read Task Details: Users can view the details of a specific task,  including its title, description, and status.
    * Update a Task: Users can update an existing task's details
    * Delete a Task: Users can delete any of their created tasks.

Installation
1. Install Python 3.12.2 in your local machine.
2. Create folder django-project in your local machine
3. Navigate to the folder created in git bash and run this code to create your virtual  
   environment.
   -py -m venv Python_Testing
4. Activate your virtual environment
   -source Python_Testing/Scripts/activate
5. Install django
    -pip install django
6. Clone the repository in your local machine. You can either use the github desktop or simply run this code in git bash.
   -git clone https://github.com/hhernandez77/django-project.git
7. Navigate to 'taskmanager' folder
   -cd hannah/taskmanager
8. Run the server
    -python manage.py runserver
9. Open http://127.0.0.1:8000/ in your web browser