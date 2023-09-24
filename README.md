# E-commerce-Back-End

## Acceptance Criteria

GIVEN a functional Express.js API  
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file  
THEN I am able to connect to a database using Sequelize  
WHEN I enter schema and seed commands  
THEN a development database is created and is seeded with test data  
WHEN I enter the command to invoke the application  
THEN my server is started and the Sequelize models are synced to the MySQL database  
WHEN I open API GET routes in Insomnia Core for categories, products, or tags  
THEN the data for each of these routes is displayed in a formatted JSON  
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core  
THEN I am able to successfully create, update, and delete data in my database

## Description

Test your developed routes on [insomnia](https://docs.insomnia.rest/)
POST, PUT, and DELETE routes for categories being tested in Insomnia  
GET routes to return a single category, a single product, and a single tag being tested in Insomnia  
Please upload a walkthrough video demonstrating the POST, PUT, and DELETE routes for products and tags being tested in Insomnia

## Getting Started

You’ll need to use the [MySQL2Links](https://www.npmjs.com/package/mysql2) and [SequelizeLinks](https://www.npmjs.com/package/sequelize)packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) to an external site. to use environment variables to store sensitive data, like your MySQL username, password, and database name.

Use the schema.sql file in the db folder to create your database using MySQL shell commands. Use environment variables to store sensitive data, like your MySQL username, password, and database name.
