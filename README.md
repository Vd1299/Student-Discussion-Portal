# Student-Discussion-Portal
This is a student Discussion portal made using Pythons Django framework, SQLite Database and HTML, CSS and JavaScript on Frontend to address the issue of international students.

# Steps to run the project
**Prerequisites:** Install python by downloading python from official website. You will always get the latest version of the python from official website.

**Virtual Environment:** It is recommended to create a virtual environment as it keeps your project environment separate from your everyday use environment. Run the following code on command prompt at location where you have saved the project. Once the enviornment was created I moved it inside the project folder but not mandatory.
•	Python -m venv environment_name
•	Source environment_name\scripts\activate #for windows
•	Source environment_name/bin/activate #for macOS/Linux

**Django Installation:** Use following command in command prompt after virtual environment is activated “pip install django” it will install Django in virtual environment

**Clone the project Repository:** Clone the project from source control using “git clone” command, or download zip file and extract and open project in Microsoft Visual code.

**Perform Migrations:** By making use of following commands migrate the project by using terminal in VS code.
•	python manage.py makemigrations
•	python manage.py migrate

**Start local server:** Launch the project by running following command in terminal “python manage.py runserver” it will run the project on localhost at http://127.0.0.1:8000/ the port 8000 can differ.
