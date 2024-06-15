# CiPanel - Advanced Modular Admin Panel + CRUD & API Builder

## Server Requirements

**Note You will need the following sofwares**

Local Engine (eg: Xampp, WampServer, etc)
Web Server (eg: Apache, Nginx, etc)
Database Engine (eg: MySQL, MariaDB, etc)
Database Client (eg: DBeaver, Navicat, etc)
Code Editor (eg: VSCode, Sublime, etc)
Web Browser (eg: Chrome, Firefox, etc)
Rest API Client (eg: Postman, Swagger UI, etc)..

**You will need the following extensions**

PHP version 7.3 or higher
PHP Composer version 2.6 or higher

**Extensions/seetings listed below are installed/enabled**

- intl
- mbstring
- json
- MySQLi
- GD
- cURL
- mysqlind
- xml

## CiPanel Installation

This is the native version of the project with the standard Codeigniter 4 framework. We recommend using this version only for experienced developers.

Running the local project is very simple, just follow the step by step below:

- Copy the CiPanel.zip and unzip to your directory.
- Open the console in the project folder and run the "composer install" command to install CiPanel deppendencies.
- Copy the file env to .env and update the database configuration.
- In the console, run the command "php spark migrate" command to create the database structure.
- In the console, run the command "php spark db:seed DataSeeder" to insert data into the database.
- In the console, run the command "php spark serve --port 8000", it will be started at the default url "https://localhost:8080".
- To access, use the default username "admin@admin.com" and the password "P@ssw0rd"

## Contact Us

- digihub.co.id@gmail.com
