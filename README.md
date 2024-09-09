# E-Commerce Back-end

A simple command line application that can be used to create SVG logo fies.The application enables users to enter inputs into a inquirer prompt in order to generate a logo "logo.svg" file which contains the users desired results as an SVG image.

## Description
This repo contains the back-end code to manage an e-commerce site. The main objective of this project is to use  Object-Relational Mapping, which allows us to convert data between incompatible systems using object-oriented programming. ORM libraries, such as Sequelize, allow us to make calls to the database without having to write SQL queries, and can instead use Javascript. This project uses node.js, npm, express.js, sequelize, postgreSQL, and dotenv packages. There is no front-end for this app, therefore all interactions with the app go through Insomnia. The walk-through video below demonstrates the apps functionality.



## Getting Started
The following animation demonstrates the application functionality: 
![A user can input the logo text, text color, shape of the logo and logo color using the command prompt.](./Assets/Demo-video.mp4)

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)
### Dependencies

* express 4.17.1
* dotenv 8.2.0
* pg 8.11.3
* sequelize 5.21.7

### Installing

* Clone the repo: git clone https://github.com/aniraannu/SVG-logo-maker

* Open in VS Code. If you do not have VS code you must install it.

* Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16), however this may vary and the documentation should be consulted.

* Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

* Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install inquirer and jest directly from the command line, to do so the command for inquirer will be npm i inquirer@8.2.4 to install v8.2.4 of the inquirer, and npm i jest to install the latest version of jest).

* Start the Server, Sync the Sequelize models to the PostgreSQL database.

* User will need to use the PostgreSQL and Sequelize packages to connect your Express.js API to a PostgreSQL database and the dotenv package to use environment variables to store sensitive data.

* Use the schema.sql file in the db folder to create the database with PostgresSQL shell commands.

* Use environment variables to store sensitive data such as: PostgreSQL username, password, and database name.

* Run npm run seed to seed data to the database to test the routes.

### Executing program

* The application code can be cloned from the following Github link:
[GitHub-E-Commerce-back-end](https://github.com/aniraannu/E-Commerce-back-end)

## Help

NA

## Authors

Contributors names and contact info

Anira Raveendran
[@aniraannu](https://github.com/aniraannu)

## Version History

* 0.1
    * Initial Release

## License

None

## Acknowledgments

Inspiration, code snippets, etc.

* [dbader](https://github.com/dbader/readme-template)
* [Starter-Code]