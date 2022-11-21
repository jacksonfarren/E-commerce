# E-commerce

![Badge](https://img.shields.io/badge/License-MIT-yellow)
![Badge](https://img.shields.io/github/languages/top/jacksonfarren/E-commerce)

## Description
The goal of this application was to build a simple back end for an E-commerce site. Through the use of SQL Databses, Express.js API, Sequelize and more. The focus of the back end is to allow for api endpoints to retrieve 
specific data relating to certain database modules. 

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)

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
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Installation

To use this application, clone the repository and make sure you have node.js and mysql installed. From there, it's simple. Open the terminal and cd into the repository directory. Since the package.json dependencies have the required moduels, in the terminal type `npm i`. Once the required modules are finished installing, you will want to enter the mysql shell where you can source the database. Once sourced, make sure that databse is in use with the command `use (database name)`. From there, quit the shell and seed the database from the integrated terminal. Since there is a script for seeding just make sure you are in the root directory for the project and type `npm run seed` into the terminal and press enter. This will seed the database. Once that is complete, you can test the individual endpoints through Insomnia core. You can view how to test these enpoints through the walkthrough video listed below. 

## Usage

### Video Demonstration

<!-- ![demonstration](/assets/demonstration.gif) -->

<!-- For the full video. See <a href='https://youtu.be/YvmLyR0MgOA' target='_blank'>Demonstration</a> -->

## Credits 

[Jackson Farren](https://github.com/jacksonfarren)

## License

![Badge](https://img.shields.io/badge/License-MIT-yellow) </br>
This application is licensed under MIT. To see more check out
[License](/LICENSE).