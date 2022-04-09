Running this project
To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install virtualenv with

pip install virtualenv
Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

virtualenv env
That will create a new folder env in your project directory. Next activate it with this command on mac/linux:

source env/bin/active
Then install the project dependencies with

pip install -r requirements.txt
Now you can run the project with this command

python manage.py runserver
Note if you want payments to work you will need to enter your own Stripe API keys into the .env file in the settings files.

more details about installation : 

Installation
pip install django

virtualenv env

For Mac/ Linux
source env/bin/activate

For Window
env\scripts\activate

pip install -r requirements.txt

python manage.py makemigrations

python manage.py migrate

python manage.py runserver


For Admin Login
python manage.py createsuperuser
Username : admin
Password : 12345678



<h4>Any further query? just feel free to contact at (me@sayeedhossain.com) </h4>

