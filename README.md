# 13 Object-Relational Mapping (ORM): E-Commerce Back End
# e-commerce-back-end

## Description

In this project I build the back end for an **e-commerce** site by modifying starter code. I configure a working Express.js API to use Sequelize to interact with a MySQL database.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Instructions

```md
This program uses a functional Express.js API
You are able to add a database name, MySQL username, and MySQL password to an environment variable file
Which is then able to connect to a database using Sequelize
After you enter schema and seed commands to your command line or other application
you can run a development database that is created and is seeded with your test data
After you enter the command to invoke the application
Your server is started and the Sequelize models are synced to the MySQL database
Once open API GET routes in Insomnia Core for categories, products, or tags
The data for each of these routes is displayed in a formatted JSON
Then you can test your API POST, PUT, and DELETE routes in the Insomnia Core
Afterwards you will be able to successfully create, update, and delete data in your database
```

## Mock-Up

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia Core:

![In Insomnia Core, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./assets/images/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia Core:

![In Insomnia Core, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./assets/images13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia Core:

![In Insomnia Core, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./assets/images/13-orm-homework-demo-03.gif)

## Technology

the program uses the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect the Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

### Walkthrough Video:
