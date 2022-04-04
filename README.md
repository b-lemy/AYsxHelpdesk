<br> AysxHelpDesk  </br> 
a ticketing system that will be used by the helpdesk to provide assistance to our client. This is just a simple Django helpdesk web application that I am building to solve a problem at my workplace and to better test and expand my abilities

Installation Clone Repo:

git clone Change Directory to the Cloned Repo:

cd django-helpdesk Create Virtual Environment:

virtualenv hdenv Activate Environment:

Windows: hdenv\Scripts\activate Linux: source hdenv/bin/activate Install Requirments:

pip install -r requirements.txt Run Migrations:

python manage.py makemigrations python manage.py migrate Run Server:

python manage.py runserver
