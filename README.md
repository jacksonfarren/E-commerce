# E-commerce

![Badge](https://img.shields.io/badge/License-MIT-yellow)
![Badge](https://img.shields.io/github/languages/top/jacksonfarren/E-commerce)

## Description
The goal of this application was to build a console application that can take in user inputs and through inquirer display the answers through an integrated html template. The user can select from a list of employee options and from there, declare that employee's name, id, email etc. Once finished, the application takes in all the data and integrates it through the template script which is then used to display the actual generated html page to which the data will be displayed.

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

To use this application, clone the repository and make sure you have node.js installed. From there, it's simple. Open the terminal and cd into the repository directory. Since the package.json dependencies have the required moduels, in the terminal type `npm i`. Once the required modules are finished installing you can just type `node index.js` into the terminal and the questions will begin. To see the full installation and run through of the code, watch the video in the usage section of the README.

## Usage

### Video Demonstration

![demonstration](/assets/demonstration.gif)

For the full video. See <a href='https://youtu.be/YvmLyR0MgOA' target='_blank'>Demonstration</a>

## Credits 

[Jackson Farren](https://github.com/jacksonfarren)

## License

![Badge](https://img.shields.io/badge/License-MIT-yellow) </br>
This application is licensed under MIT. To see more check out
[License](/LICENSE).