# Task-Manager-Flask
Simple Todo Flak app that will help you to manage your tasks

- For running
  - **Pre-requisite**
      1. Python
      2. Flask
      3. flask-sqlalchemy
      4. pip
   
    ```bash
      pip install flask flask-sqlalchemy
    ```

  - Db creation (can be done in app but do on python shell):
    ```bash
      python
      from app import db
      from app import app

      with app.app_context():\
        db.create_all()
    ```
    now run by command:
    ```bash
      python .\app.py
    ```
    will start serving usually on **http://127.0.0.1:5000** but can differ can see from terminal.
      
      
