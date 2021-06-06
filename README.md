# e-commerce-back-end [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

## Description

* This app works as a back-end for an e-commerce site. The app gives users the ability to GET ALL, GET 1, UPDATE, CREATE, and DELETE data entries for Product, Category, and Tags tables for the e-commerce site.

 ## Table of Contents

1. [Description](#Description)
2. [Technologies](#Technologies)
3. [Installation](#Installation)
4. [Walkthrough](#Walkthrough)
4. [Usage](#Usage)
4. [License](#License)
4. [Contributing](#Contributing)
4. [Tests](#Tests)
4. [Author](#Author)
4. [GitHub](#GitHub)


## Technologies
* Express.js
* MySQL2
* Sequelize
* Dotenv

## Installation
1. Clone repository
2. In the application's root terminal type `npm install`
    * This will install all the dependencies listed in package.json
3. Create an .env file at root of application and insert MySQL credentials (username & password). DB_Name must be 'ecommerce_db'.
    * DB_NAME='ecommerce_db'
    * DB_USER='username'
    * DB_PW='password'

## Walkthrough
* Walkthrough video [link](https://drive.google.com/file/d/1NhVI9K_RlhmehK_Ag-PMCcErovEmOK3d/view)

## Usage
1. At application's root, connect to mysql and run "source db/schema.sql". (Creates ecommerce_db)
2. Exit out of mysql, and type "npm run seed" at application's root. (Populate tables with data)
3. Initiate the server with "npm start"
4. Now, you can run GET, POST, PUT, DELETE requests with Insomnia App.

## License
This project is in the public domain and free for any and all users! For more information on this (un)licensing statement, visit https://unlicense.org/

## Contributing
* If you'd like to contribute to this project, please follow the rules of the [Contributor Covenant](https://www.contributor-covenant.org/)

## Tests
* No testing instructions

## Author
This application was written and developed by Ronan Galvez for Module 13th's challenge assignment of the UCF Coding Bootcamp. For any questions/suggestions/concernes, open an issue or contact me directly at [galv.ronan@gmail.com](galv.ronan@gmail.com). Check out the rest of my work on GitHub at [Ronan-Codes](https://github.com/Ronan-Codes).

## GitHub
 * [GitHub Repository](https://github.com/Ronan-Codes/e-commerce-back-end.git)
