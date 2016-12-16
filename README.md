# To do list Application allows you to add your todo list items and click on the item to mark it as complete and click x button to delete the item.

Bakcend: Python, Django
Database: Sqlite
Front End: Javascript, Jquery, Bootstrap, CSS, Html

Steps to run the application

1. Clone the repo to your local machine. If you are using mac osx 
Open the teminal and goto Deskto
cd Desktop
mkdir todo
cd todo

2. Create a virtual environment and activate it
virtualenv env
source env/bin/activate

3. Install the dependencies
pip install -r requirements.txt

4. do migrations
python manage.py makemigrations
python manage.py migrate

5. run the project
python manage.py runserver

6. Browser
open the browser and type the url localhost:8000 and hit enter and the application is loaded
