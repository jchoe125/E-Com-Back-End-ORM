
# E-Commerce Backend (Object-Relational Mapping)

## Description 
This project is the creation of the back end for an e-commerce site. This application utilizes Express.js API and Sequelize in order to interact with a SQL database using models and the implementation of API Routes to perform RESTful CRUD operations via Insomnia.

## Table of Contents
* [Installation](#installation)
* [Acceptance-Criteria](#acceptance-criteria)
* [Usage](#usage)
* [License](#license)
* [Questions](#questions)
* [Submission](#submission)

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

View video to see MySQL walk through via [Screencastify](https://drive.google.com/file/d/1rGknm_dCHlzDqsICb5eWbsOfmPPLq0q5/view)<br>
View video to walk through of the API routes. [Screencastify](https://drive.google.com/file/d/1KDgDctcv66DZwJ4sRQ25_R7aBmImfU5y/view)<br>
View video to see Insomnia walk through via [Screencastify](https://drive.google.com/file/d/19GbrbxORiqPIEN0aaUVtRSq8gyA8yN_B/view)

## License 
This project is licensed under:  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://img.shields.io/badge/License-MIT-yellow.svg)

# Questions
If you have any questions, please send them to my GitHub profile: https://github.com/jchoe125

# Submission
* GitHub: https://github.com/jchoe125/E-Com-Back-End-ORM


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

* A walkthrough video that demonstrates the functionality of the e-commerce back end must be submitted, and a link to the video should be included in your readme file.

* The walkthrough video must show all of the technical acceptance criteria being met.

* The walkthrough video must demonstrate how to create the schema from the MySQL shell.

* The walkthrough video must demonstrate how to seed the database from the command line.

* The walkthrough video must demonstrate how to start the application’s server.

* The walkthrough video must demonstrate GET routes for all categories, all products, and all tags being tested in Insomnia.

* The walkthrough video must demonstrate GET routes for a single category, a single product, and a single tag being tested in Insomnia.

* The walkthrough video must demonstrate POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia.

### Technical Acceptance Criteria: 40%

* Satisfies all of the preceding acceptance criteria plus the following:

  * Connects to a MySQL database using the [MySQL2](https://www.npmjs.com/package/mysql) and [Sequelize](https://www.npmjs.com/package/sequelize) packages.

  * Stores sensitive data, like a user’s MySQL username, password, and database name, using environment variables through the [dotenv](https://www.npmjs.com/package/dotenv) package.

  * Syncs Sequelize models to a MySQL database on the server start.

  * Includes column definitions for all four models outlined in the homework instructions.

  * Includes model associations outlined in the homework instructions.

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality readme with description and a link to a walkthrough video.

## Review

You are required to submit BOTH of the following for review:

* A walkthrough video demonstrating the functionality of the application and all of the acceptance criteria being met.

* The URL of the GitHub repository. Give the repository a unique name and include a readme describing the project.
