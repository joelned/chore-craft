# Chore Craft

This is a simple task manager API built using Flask and SQLAlchemy. It allows you to add, update, and delete tasks, while managing them in a SQLite database.

## Getting Started

Follow the steps below to get the project up and running on your local machine.

### Prerequisites

Make sure you have Python 3.8 or higher installed on your system.

### Step-by-Step Setup

1. **Clone the repository**

   First, clone the repository to your local machine. Replace the URL with the actual URL of your repository.

   ```bash
   git clone https://github.com/yourusername/flask-task-manager.git
   cd flask-task-manager
   ```
2. **Set up a python virtual environment**
   It's highly recommended to create a virtual environment to manage dependencies.

   For Windows:
   ```bash
   python -m venv env
   ```
   For Mac/Linux:
   ```bash
   python3 -m venv env
   ```
3. **Set up a python virtual environment**

    For Windows:
    ```bash
     .\env\Scripts\activate
     ```
    For macOS/Linux:
     ```bash
     .\env\bin\activate
     ```
4. **Install the required dependencies**
     With the virtual environment activated, install Flask, SQLAlchemy, and Flask-Migrate using pip:
    ```bash
     pip install flask flask_sqlalchemy flask_migrate
    ```
5. **Set up the database**
     If you're setting up the app for the first time, you need to initialize the database. Run the following commands to set up migrations:
      ```bash
        flask db init
        flask db migrate -m "Initial migration"
        flask db upgrade
      ```
6. **Run the application**
      ```bash
          python app.py
      ```
This will start the app on the default port, usually http://127.0.0.1:5000/.
      

       




