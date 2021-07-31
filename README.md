# E-commerce-back-end

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Description
The purpose of this is to have functional back-end code for an E-commerce store.
A database can be created and seeded using the files within.  Utilizes sequelize to connect to the database, and has a functional Express.js API.  There are routes to successfully GET, POST, PUT, and DELETE routes for products, categories, and tags--  using a program similar to Insomnia Core.


 
## Table of Contents 
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contribution](#contribution)
* [Tests](#test)
* [Questions](#questions)
    
## Installation    
 After cloning and in your directory:

```bash
npm init -y
```
```bash
npm install
```


## Usage 
Create a .env file for the database, user, and password so that it remains private.
To create database from mySQL shell:
```bash
mysql -u root -p
```
Enter your password and then:

```bash
source db/schema.sql
```
To seed database:
```bash
npm run seed
```
To run this program, after installation type the following into the terminal while in the program's directory

```bash
npm start
```
Then routes can be tested in a program such as Insomnia.
## License
This project is licensed under the mit license.
    
## Contribution 
    
Was given code to finish from Georgia Tech's FSF Bootcamp.

If you wish to make contributions, please contact me below, first.



![Video demonstrating the usage](https://github.com/roomsiejones/E-commerce-back-end/blob/main/E-commerce-test.gif?raw=true)
## Questions
To contact me or report issues, please email me at jonathonrenaud1988@gmail.com
Go to https://github.com/RoomsieJones to view my github profile.    

## Link to Repository
[Link to repository!](https://www.github.com/roomsiejones/E-commerce-back-end)