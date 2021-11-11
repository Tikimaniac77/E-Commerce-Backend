# E-Commerce-Backend

![Badge for GitHub repo top language](https://img.shields.io/static/v1?label=License&message=ISC&color=brightgreen)

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Description

A mysql database and application backend for an e-commerce site. Built using MySQL2, Express, Sequelize and dotenv.
  
[Click the link to see the video demonstration](https://watch.screencastify.com/v/84HHwfsiX0qwaggO4Vp5)

This application should meet the following criteria:

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

`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## Usage
  
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter your password when prompted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`

## License

This project is licensed under the ISC License.