Football Teams App
This is a Symfony PHP web application that allows users to manage football teams, their players, and the buying/selling of players between teams.

Installation
To install and run the application, follow these steps:

Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your_username/football-teams-app.git
Navigate into the project directory:
bash
Copy code
cd football-teams-app
Install the project dependencies using Composer:
Copy code
composer install
Create a new database for the application and update the DATABASE_URL environment variable in the .env file with your database connection details.

Run the database migrations to create the required tables in the database:

bash
Copy code
php bin/console doctrine:migrations:migrate
Load some sample data into the database (optional):
bash
Copy code
php bin/console doctrine:fixtures:load
Usage
To run the application, start the Symfony server:

sql
Copy code
symfony server:start
The application can then be accessed in your web browser at http://localhost:8000.

Tests
To run the unit tests for the application, use the following command:

bash
Copy code
php bin/phpunit
Features
The application includes the following features:

Display a list of all football teams and their players, with pagination
Add a new football team and its players to the database
Buy/sell a player between two football teams and update the teams' money balance accordingly
Contributing
If you would like to contribute to the development of this application, please fork the repository and submit a pull request with your changes.

License
This application is developed by Evrald.
