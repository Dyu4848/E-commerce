# 13 Object-Relational Mapping (ORM): E-Commerce Back End



## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)




## Description

In this application, we are creating the backend database for an e-commerce website, such as Amazon. This application uses Express and Sequelize in order to connect with the database, and redirect it to the front end.

This is the [Link](https://drive.google.com/file/d/16askSpTooUp1zcPzO42FI2QWOiH6tZuk/view?pli=1) for my video walkthrough

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Accepance Criteria
```md
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
- dotenv
- sequelize
- express

## Usage

In this application, we are able to view, add, update, and delete content within these databases. Using insomnia to simulate the front end, I was able to manipulate the data and verify that the responses were corresponding to the code that was written out for them. So, e-commerce companies such as Amazon, can use applications such as this in order to manage and manipulate their backend storage.







