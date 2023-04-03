# Ecommerce-Store
A project that builds out the back-end of an e-commerce store using express and mySQL

## Description
This project builds out the backend of an e-commerce store using express and mySQL.  The backend will use models to store data for Products, Categories, and associated Tags.  The tags and categories will be connected to the products so they will be accesible when product data is pulled.  The backend will allow users to get, add, update and delete data for products, tags, and categories.

## User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
## Installation
The user will need to run the schema using sql, install packages using npm install and run seed data by using npm run seed.  The user will have to use a tool such as insomnia in order to simulate the various server requests.

## Usage

Video Demonstration: https://drive.google.com/file/d/1MjFbUbgpqFQzz64oHtJ9RZzO5RjkXqZY/view

Github Repository: https://github.com/JpBaer/Ecommerce-Store