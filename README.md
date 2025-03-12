# Task Management

This is a simple Task Management program that allows users to create, view, update, and delete tasks. This also includes user authentication for managing task securely.

## Features
### User Authentication
- **Authentication** ensures that each user can manage only their tasks.
- **Register an account** and log in to access the task management system.


### Task Management
- **Create a Task**: Users can create tasks by providing a title, description, and date.
- **View Task**: Users can view a list of all their created tasks.
- **Read Task Details**: Users can view the details of a specific task, including its title, description, and status.
- **Update a Task**: Users can update an existing task's details.
- **Delete a Task**: Users can delete any of their created tasks.


## Installation

1. Install Python 3.12.2 on your local machine.
2. Create a folder named `django-project` on your local machine.
3. Navigate to the folder in Git Bash and run the following code to create your virtual environment:

    ```bash
    py -m venv venv
    ```

4. Activate your virtual environment:

    ```bash
    source venv/Scripts/activate
    ```

5. Install Django:

    ```bash
    pip install django
    ```

6. Clone the repository to your local machine. You can either use GitHub Desktop or run the following command in Git Bash:

    ```bash
    git clone https://github.com/hhernandez77/django-project.git
    ```

7. Navigate to the `taskmanager` folder:

    ```bash
    cd taskmanager
    ```

8. Run the server:

    ```bash
    python manage.py runserver
    ```

9. Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your web browser.
