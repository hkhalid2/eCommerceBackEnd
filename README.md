# eCommerceBackEnd
## Description
The main motivation for creating this project was to create the back end for an e-commerce site using supplementary code. This app is configured by creating a working Express.js API that uses sequelize to interact with a MySQL database. This app is invoked in the terminal and then various route mthods are implemented in Insomnia in order to modify the Database. 

The main problems this app solves include:
* Creating a .env file in order to hold credentials for accessing the MySQL database using sequelize.
* Entering schema/seed shell commands in order to populate a database
* Updating/Deleting/Getting routes in order to change various table values in the database. 

Overall this app taught me specifically how to create various models for sequelize and routes to be used for updating/getting/deleting various tables in the database. It also familiarized me with how to execute various routes in Insomnia and how to write various JSON commands to manipulate the database.

## Installation
A simple npm i was used to install sequelize, mysql 2 and dotenv.
Dotenv was use for taking used to hide/secure the users information in a .env file, mysql was used to create the database and various tables to be used/appended and console.table was used to display table on the commandline for the user. 

``npm i``


## Usage
*Log into mysql and source schema
*``node seed``
*``node server``
*Check routes using Insomnia

## License 
MIT License

            Copyright (c) 2021 Hamza Khalid
            
            Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
            
            The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
            
            THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE
            
## Badges
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

### Demo Video
https://drive.google.com/file/d/1zQG4WphSmXeCJuBCwhv2ePaNyU7uTsJ5/view?usp=sharing
