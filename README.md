# Task Manager

## Overview
Task Manager is a web application built with Django that allows users to manage their tasks efficiently. Users can create, update, delete, and view tasks.

## Features
- User authentication and authorization
- Create, read, update, and delete tasks
- Task filtering and sorting
- Responsive design

## Installation

### Prerequisites
- Python 3.x
- Django
- Git

### Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/akaday/taskmanager.git
    cd taskmanager
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv myenv
    .\myenv\Scripts\Activate  # On Windows
    # source myenv/bin/activate  # On macOS/Linux
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. Run the development server:
    ```bash
    python manage.py runserver
    ```

## Usage
1. Open your web browser and go to `http://127.0.0.1:8000/`.
2. Register a new account or log in with an existing account.
3. Start managing your tasks!

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
If you have any questions or feedback, feel free to reach out at [your-email@example.com].

