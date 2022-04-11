# Web-Sympfony-METATRIP


Run the command : composer install within your project to install all bundles that came in.


//database configuration : Make sure to change the port number in the .env file to the port your server is using. if you want to test this project, create a database metatrip and run the command :

php bin/console doctrine:schema:update --force
To upload the entities to your database.

ERROR PAGE WHEN STARTING UP THE PROJECT :

The main route in the project is pointing on profile, however since this is not a deployed project, the database is empty and you'll have to sign up in order to be let in.


make sure to change the Port number (in my case it's 8000) to yours.

Visualize and debug routes: php bin/console debug:router to visualize all available routes and how to navigate to each one.

General questions : zakaria.dafdouf@esprit.tn
