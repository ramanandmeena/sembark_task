Project Setup Instructions
This repository contains a Laravel 10 project. Follow the steps below to set up and run the project on your local system.

Prerequisites
Before installing the project, make sure you have the following installed:
PHP: version 8.1 or higher (compatible with Laravel 10)
Composer: latest version
MySQL (or MariaDB) for database

Steps to Install the Project
Download the Project
Go to the repository link: (https://github.com/ramanandmeena/sembark_task)
Download the repository as a ZIP file.
Extract the ZIP
Right-click the downloaded ZIP file and select Extract Here (or use any extraction tool).
Open the extracted folder.
Database Setup
Inside the project folder, navigate to the database folder.
You will find a .sql file.
Open phpMyAdmin and create a new database with your preferred name.
Import the .sql file into this newly created database.
Configure Environment File
Open the project folder and find the .env file.
Update the following lines with your database details:
DB_DATABASE=your_database_name
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
Install Dependencies
Open a terminal (or command prompt) in the project folder.
Run the following command to install all required packages:
composer install
Run the Project
Start the Laravel development server with:
php artisan serve
After starting the server, open the provided link (usually http://127.0.0.1:8000) in your browser.
You should now be able to see the website running.

Notes
Ensure your PHP version matches Laravel 10 requirements (>= 8.1).
Make sure composer is installed globally on your system.
For any issues with the database, double-check the .env file configuration.

Login details
Password for all = 123456
Super admin
super@gmail.com
Admin 
admin@gmail.com
Member
member@gmail.com
