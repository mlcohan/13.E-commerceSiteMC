# E-commerceSiteMC
The back end for an e-commerce site using Sequelize

## Description
a working Express.js API using Sequelize to interact with a MySQL database

```md
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
```


## Table of Contents
* [Installation](#installation)
* [UserStory](#userStory)
* [WalkThrough](#walkthrough)
* [Questions](#questions)


## Installation
1. Clone repo <br>
```
      git clone git@github.com:mlcohan/13.E-commerceSiteMC.git
```
2. Enter your personal mySQL info in the .env.EXAMPLE file

3. Install dependencies <br>
```
      npm i
```
4. Creat Database on mySQL using schema.sql and seed.sql files

5. Add Seeds <br>
```
      npm run seed
```
6. Run app <br>
```
      node server.js
```
7. Use Insomnia to GET, POST and DELETE from the category, product and tag routes

## UserStory 
```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Walkthrough

https://drive.google.com/file/d/1Tt4xgWt6IjZWIMzh5zwHH_A905IKix-j/view


## Questions?
   
Check out my GitHub @: <br>
github.com/mlcohan

Find this code @:<br>
https://github.com/mlcohan/13.E-commerceSiteMC

Or Email Me @: <br>
mary.cohan@gmail.com

