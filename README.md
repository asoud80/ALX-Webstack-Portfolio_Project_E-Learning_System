Description of the project
__________________________

An e-learning system is a unified online platform or piece of software that provides interactive tools to educators, administrators, trainers, and students to assist in organizing and receiving educational materials.


objectives
___________

An e-learning system, also known as an LMS, is primarily designed to assist educators in creating, delivering, and tracking resources.

Technologies used
_________________

1.FrontEnd
	HTML
	CSS
	JS

2.BackEnd
	SQLite
	Python-3
	Django

3.Other
	Github

Challenges
__________________
	- Insufficient communication with teachers and fellow students
	- Technology aversion
	- Lack of motivation
	- Time-sensitive

Schedule of work
_________________
https://app.teamgantt.com/projects/gantt?ids=3962819

About me
____________
My name is Amgad Aboul Seoud, ALX graduate with software engineer, full stack developer. this project was designed by the following technologies MySQL database and HTML, CSS & some JavaScript. I am graduated form faculty of  Computer and artifical intellegnce , I'm also a master dgeree in software engineering.  i have a good experience in ERP Project Managment. I love coding and I want to be web and application developer. I’m passionate about creating truly beautiful, efficient and problem solving softwares.

Installation
__________________
The first thing to do is to clone the repository:

https://github.com/asoud80/ALX-Webstack-Portfolio_Project_E-Learning_System

Then make sure your machine is capable to run the code. The below command is for Linux OS
sudo apt-get install python3.*
sudo apt install python3-django
pip install django-crispy-forms
pip install django-ckeditor

Navigate to the folder containing the manage.py file. Next, establish a superuser account so that administrators can view and edit the admin page.

python3 manage.py createsuperuser
"""Then follow the stapes and provide the information needed."""


Then, it is time to run the program. Simply type the command below without modifying your directory.

python3 manage.py runserver
"If you want to run it with different port, use the below"
python3 manage.py runserver <port_no_you_want>

Setting
_________

You can deploy this system with two different database system, MySql or sqlite. Just open setting.py file located in .../elearning directory make adjustment as be below.

To run with sqlite database, make sure to uncomment the below code and comment any code line start with "DATABASES = {"

 DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': BASE_DIR / 'db.sqlite3',
    }
 }

To run with MySql database, make sure to uncomment the below code and comment any code line start with "DATABASES = {"

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': '<name_of_your_schema>',
        'USER': '<user_name_with_write_privilege>',
        'PASSWORD': '<password>',
    }
}
