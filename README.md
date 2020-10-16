# Burger Boi
  [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
  ![burger boi](./public/assets/imgs/burgerBoi_small.JPG)
  ## Description 
  A simple Web app using the ORM and VCM principrincipals using express, handlebards, and mysql. Deployed on Heroku. Server.js begins the whole thing listening on part 8080. controllers/burgerController.js takes in url routes and either sends data to the views (handled by handlebars), or uses the custom ORM functions to create or update the data in the MySQL database. 
  
  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [Credits](#credits)
  * [License](#license)
  * [Contributions](#contributing)
  * [Tests](#tests)
  
  ## Installation 
  Upon cloning the repository, you will need to ```NPM install``` to get dependencies. You will need to setup your db by using the schema and optional seeds sql files in db. Run schema either in workbench or using ```mysql -> source schema.sql```
  
  ## Usage
  After your localhost is setup, navigate to localhost:8080 in your web browser. Simply type in the name of your burger and add it to the list, you can eat the burger to add it to the devoured list
  
  ## Credits
  Thanks to the instructors and staff at uw/trilogy for the starter code and the ORM helper functions
  
  ## License
  MIT
  
  ## Contributing
  Not taking contributions at this time
  
  ## Tests
  none
  
  ## Questions
  Have quesitons about this repo? Please reach out on github or via email
  * [clubkemp](https://github.com/clubkemp)
  * kempj2.jk@gmail.com