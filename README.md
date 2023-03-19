# Object-Relational Mapping (ORM) Challenge: E-commerce Back End


## Description
The challenge was to build the back end for an e-commerce site. Take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## Usage
***
By utilizing Node.js, Express.js and MySQL 2 we can create a command-line application that dynamically generates an employee database. 

To install, please use:

```
npm i 
```
To install MySQL 2:
```
npm i mysql2
```

To engage MySQL:
```
mysql -p
```
or
```
mysql -u root -p
```
To seed the data, please use:
```
node ./seeds/index.js
```
The server will start by using the following command:
```
npm start
```



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

## Link to Walk-through Video
https://drive.google.com/file/d/1uYYWBU9BdMqHl6-BBTnehnXMbwGV-f8w/view

![Screenshot](./assets/Screenshot%202023-03-18%20192748.png)

### Sources

- Instructor: Bassie B.; TA - Ethan D.; Tutor: Jacob C. - reference to the 'mini project'