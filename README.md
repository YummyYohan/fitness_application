# fitness_application

This is a Flask local API.

##Setup
1. there is a requirements.txt where you can download the dependencies.

   pip install -r requirements.txt
   
3. API.py is the API application using Flask.
4. fitness_database.ipynb is just a jupyter notebook code showing what I did in order to create my database. You dont have to do anything with it, just as a reference.
5. fitness_dump.sql is the copy of the database that I created running fitness_database.ipynb. You can do

   mysql -u root -p fitness < fitness_dump.sql

   in order to import it to your local MySQL. if it ever asks for a password, its just "yummy".
   
