# roseluu-ORM-e-commerce

 [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://choosealicense.com/licenses/mit/#)

  # Table of Contents 
  * [Installation](#installation)
  * [Technologies](#technologies)
  * [Usage](#usage)
  * [License](#license)
  * [Contribution](#contribution)
  * [Questions](#questions)
 
 # Walkthrough video link : 
  
  [Instructor Video](https://drive.google.com/file/d/1L1wMlP3HTvJHmFFJMlEfGyKj3rlMqS51/view)
  
  # Description
  This project will build the back-end for E-commerce page. Using sequelize to interact with SQL database.

  <br />

  # Installation
  User have to install:
  * [Node.js](https://nodejs.org/en/download/)
  * Sequelize
  * Express
  * MySQL2
  * dotenv
  * Insomnia

  # Technologies
  * JavaScript
  * Node.js
  * SQL

  # Usage
  Clone this repo, open terminal (on Mac) or GitBash (on Window), navigate to the file and run command 
  ```
  npm i
  ```
  to install Sequelize, Express,  MySQL2 and dotenv.

  <br />

  Navigate to `db` folder and run mysql to install the database
  ```
  mysql -u root -p
  ```
  after enter your sql password, run
  ```
  source schema.sql
  ```
  to create database. Then exit the database by run:
  ```
  exit
  ```
  <br />

  After that get out to the root level and run the command
  ```
   node seeds/index.js
  ```
  to create table and column inside the database
  <br />

  To start retrieve the data. Run this command:
  ```
  node server.js
  ```
  Use Insomnia to interact with database by GET, POST, PUT and DELETE.
  # License
  This project is licensed under the MIT license. 

  # Contribution
  ​Contributors: 
  Rose Luu

  # Questions
  Please contact if there is any question:
  - Github: [RoseLuu](https://github.com/RoseLuu)
  - Email: luuhongnhung10@gmail.com 