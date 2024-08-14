# E-Commerce Back End

## Description

This E-Commerce Back End utilises object-relational mapping (ORM), PosgreSQL and Sequelize to perform CRUD operations on an ecommerce database. Within this application, users are able to add their details to an environment variable, connect to a database using Sequelize, seed existing data and then perform API GET, POST, PUT and DELETE operations on the data. This allows the users to update, delete and create data within the E-Commerce database. This application has allowed me to utilise and learn about CRUD applications, practice a range of API calls on a database, learn about ORM and practice utilising Insomnia. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Credits](#credits)
- [Contributing](#contributing)
- [Features](#features)
- [Questions](#questions)

## Installation

To utilise the E-Commerce Back End, users must first clone the repository. Once cloned, with VS Code's terminal the user must copy the .env.example file and enter their PostgresSQL details. Within VS Code's terminal, run 'npm i' to install any required packages and npm start to test the server is working. Once users see the 'App listening on Port' message on their terminal, exit the server. 

To start the open the shell and run the database, run 'psql -U postgres' in the terminal and enter a password. Enter '\i schema.sql' to initialise the database and once successful, exit the shell. 

To seed the database with data, enter 'npm run seeds' in the VS Code's terminal. 

## Usage

This generator can be used by entering 'npm start' within VS Code's terminal and then making API calls within Insomnia 

[Initialising the app - VS Code Demo](https://drive.google.com/file/d/1rDks2zpgnn0xrAAuTQ8svfdOk5r4Bjpd/view?usp=sharing)

[Insomnia Demo](https://drive.google.com/file/d/1X2KiDncLbuGevqeU-Xtb7ujApz6rQO_a/view?usp=sharing)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under [MIT License](https://opensource.org/licenses/MIT).

## Credits

Starter code for this project was taken from [coding-boot-camp/bookish-sniffle](https://github.com/coding-boot-camp/bookish-sniffle).

Assistance for this project was provided by the AI Xpert Learning Assistant within Bootcamp Spot. This assistance included answering questions, explaining concepts, debugging code and providing code examples. Assistance was also provided via the class Instructor in Office Hours, who helped in providing direction and explaining concepts related to the project, and via a Bootcamp Tutor who assisted in debugging code errors.

## Contributing

If you would like to contribute to the project and make it better, please feel free.

## Features

- Utilise data and ORM
- Perform CRUD operations to alter API data
- Utilise Sequelize and PostgreSql

## Questions

For any additional questions, please reach out to me on GitHub [here](https://github.com/ashlynmcgarry) or via email at ashlynjanexx@gmail.com.
