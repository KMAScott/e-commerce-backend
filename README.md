# E-commerce Back End

## Description
This project is a mysql database and application backend for an e-commerce site. It was made using MySQL2, Express, Sequelize, and dotenv.

Below is a gif demonstrating the functionality of the application:

![CRUD](./demo-gif/demo.gif)

This video can also be seen at: https://drive.google.com/file/d/1X0uGMKS1zl7dE85XAM3_c9YAatc1sqaT/view

## Installation
Run these commands to install the dependencies:

`npm init`

`npm install mysql2 sequelize dotenv express`

Create a file in the root of your project called ".env".
In this file, store your MySQL login information in the variables DB_NAME, DB_USER, AND DB_PASSWORD.

## Usage 
Run the following commands at the root of your project:

`mysql -u root -p`

Enter your password when prompted.

`source db/schema.sql`

`quit`

`npm run seed`

`npm start`

## Questions
Contact me with any questions: [email](mailto:burnbright987@gmail.com) , [GitHub](https://github.com/KMAScott)