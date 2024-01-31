# Online-Course-App-using-Django

-Added course assessment feature
-Created question, choice, and submission models
-Created a new course object with exam-related models using the admin site.
-Updated the course details template to show questions and choices.
-Created a new exam result template to show the result of the submission.
-Created a new exam result submission view.
-Created a new view to display and evaluate the exam results.


1. Set up a virtual environment to contain all the packages needed.
Type the below commands on the terminal:
pip install --upgrade distro-info
pip3 install --upgrade pip==23.2.1
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate


2. Set up the Python runtime and test the project.
Type the below command on the terminal:
pip install -U -r requirements.txt

 
3. Create the initial migrations and generate the database schema:
Migrations are Django's way of propagating changes you make to your models (adding a field, deleting a model, etc.) into your database schema. They are designed to be mostly automatic, but you will need to know when to make migrations, when to run them, and the common problems you might run into. There are several commands which you will use to interact with migrations and Django's handling of database schema:-
a) migrate, which is responsible for applying and unapplying migrations
b) makemigrations, which is responsible for creating new migrations based on the changes you have made to your models
c)sqlmigrate, which displays the SQL statements for a migration
d) showmigrations, which lists a project's migrations and their status
Type the below command on the terminal:
python3 manage.py makemigrations
python3 manage.py migrate


4. Run the server successfully this time.
Type the below command on the terminal:
python3 manage.py runserver
 
