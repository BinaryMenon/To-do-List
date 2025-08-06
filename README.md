Flask To-Do List App
A simple CRUD (Create, Read, Update, Delete) to-do list application built with:

Flask (Python web framework)

SQLAlchemy (Database ORM)

SQLite (Lightweight database)

Features
✅ Add new tasks
✅ View all tasks (sorted by creation date)
✅ Update existing tasks
✅ Delete tasks

Setup & Run
1. Install Dependencies
sh
pip install flask flask-sqlalchemy
2. Run the Application
sh
python app.py
The app will start at http://localhost:5000

The database (test.db) will be created automatically on first run.

3. Usage
Add Task: Enter a task in the input field and click "Add Task".

Update Task: Click "Update", modify the task, and submit.

Delete Task: Click "Delete" to remove a task.

Project Structure
text
flask-todo-app/  
│── app.py             # Main Flask application  
│── test.db            # SQLite database (auto-created)  
└── templates/  
    ├── index.html     # Homepage with task list  
    └── update.html    # Task update form  
Troubleshooting
If you get no such table: todo, delete test.db and restart the app.

Ensure Flask & SQLAlchemy are installed correctly.

Enjoy managing your tasks! 🚀
