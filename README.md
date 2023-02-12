# Learning-Management-System-using-Django


# Basic Principle/Architechture
This project is basically based on a renowned E-learning website: UDEMY. In this project we can see different 
web-pages with different functionality(Home, About us, Login, Signup etc.) and different courses which are 
listed in the 'All courses' page. The website has the functionality which shows enrolled courses in a 
different page. In this project we have used the basic functions, class & models are used to make every 
different functionality. In this project we have the 'update password' option which sends the confirmation 
code to your website as the real website works. For that we need to register our mail address inside a file 
and we have to give the acces to the mail.


--> Here 'LMS' is the project folder & 'app' is the project app


Tool Used: Python, Django, SQLITE3, HTML, CSS, Javascript etc.


# Step-1: Creating Virtual Environment
Use the command: python -m venv "env-name you want to set"
Example: python -m venv myenv


# Step-2: Changing directory
Use the command: cd "project directory name"
Example: cd LMS


# Step34: Installing requirements.txt
Use this command: pip install -r requirements.txt


# Step-4: Migrate all the changes into the database
Use this command: python manage.py migrate


# Step-5: Creating super user to acces the django-admin panel
Use this command: python manage.py createsuperuser


# Step-6: Run the WSGI server
Use the command: python manage.py runserver

--> Please check the server which is running in console is Development server or not

--> Go to any browser and search for: http://localhost:8000
