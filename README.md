# College Mitra
Colleg Mitra is a web and mobile application which deals with difficulties faced by the college aspirants during their college life.
1.Attendance
2.Resources
3.discussion Forum

# Platform Dependenices
We have used HTML, CSS, JS in front-end and Django(a python bsaed framework) for backed.
In mobile application we have used react-native(a javascript framework for mobile application) for cross - platform experience 
and better saclibility.

# How to deploy
Web:

Create a virtual environment in which to install Python pip packages. Virtual environment activation with virtualenv,

virtualenv venv          # create virtualenv venv
source venv/bin/activate # activate 
or with virtualenvwrapper,

mkvirtualenv myproj       # create and activate environment
workon myproj             # reactivate existing environment

Setup database tables,

python manage.py syncdb  # create neccessary tables
Run the web application locally,

python manage.py runserver # 127.0.0.1:8000

Mobile:
by using expo client.
A url address is provided, copy that url to expo clients adress and you are good to go.

#Followimg are some screenshots
![alt text](https://github.com/kshtiijsu/college_life_hackdunhack/blob/master/img/1.PNG)
