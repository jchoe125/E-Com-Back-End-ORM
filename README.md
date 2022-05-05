
# E-Commerce Backend (Object-Relational Mapping)

## Description 
This project is the creation of the back end for an e-commerce site. This application utilizes Express.js API and Sequelize in order to interact with a SQL database using models and the implementation of API Routes to perform RESTful CRUD operations via Insomnia.

## Table of Contents
  - [Installation](#installation)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Usage](#usage)
  - [License](#license)
  - [Questions](#questions)
  - [Submission](#submission)

## Installation 
The user should start by first cloning the repository from GitHub. Additionally, this application requires the user to install Node.js, Express.js, and Sequelize frameworks. To connect to the database, the user must run the command `mysql -u root -p` and enter password from the .env file and source the schema.sql file. To seed the file, the user must run the command `npm run seed`. Lastly, the user can connect to the server by running the command `npm start`. 

## Acceptance Criteria

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

## Usage 
This application will allow users to view, add, edit, and delete categories, products, and tags.

Video Walkthrough:

![Video Walkthrough gif](./assets/E-Com-Back-End%20ORM%20Video%20Gif.gif)

## License 
This project is licensed under:  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://img.shields.io/badge/License-MIT-yellow.svg)

# Questions
If you have any questions, please send them to my GitHub profile: https://github.com/jchoe125

# Submission
* GitHub: https://github.com/jchoe125/E-Com-Back-End-ORM
* Walkthrough Video: https://drive.google.com/file/d/1Z9YuRv7SQzh8yZ7dwU7gmWEWInWVvVNM/view

