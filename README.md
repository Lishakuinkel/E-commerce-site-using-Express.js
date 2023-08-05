# E-Commerce Back End using Mysql, Sequelize and Express.js

This project is mainly focused on building the back end of an e-commerce site that uses the command line interface (CLI) and object-relational mapping for various methods of data manipulation, storage, and retrieval when using HTTP methods with a RESTUL API.

It utilizes Express.js API that uses Sequelize to interact with a MySQL database.


## Installation

Run 'npm i' in CLI

## Usage

First, install all dependencies:
```
npm install
```
Next, create a .env file in the root directory and insert your db config:
```
DB_NAME='blog_db'
DB_USER='root'
DB_PASSWORD='Your Password'
```
Assuming you have mysql setup, run this command and enter your password:
```
mysql -u root -p
```
Then you need to initiate the db/schema:
```
source db/schema.sql
```
Exit the mysql cli and run the seed script:
```
npm run seed
```
Finally, you can run the application:
```
npm start
```

Testing can be done in a browser or Insomnia app. 


## Walkthrough video
[Db seeding.webm](https://github.com/Lishakuinkel/E-commerce-site-using-Express.js/assets/130411719/bdedbb49-5039-4817-88f7-8f1af6228ff4)

[Insomnia testing.webm](https://github.com/Lishakuinkel/E-commerce-site-using-Express.js/assets/130411719/e51d9736-0e1d-4b85-bff3-ff3086d53b09)

## Resources

https://www.npmjs.com/package/sequelize

https://www.w3schools.com/nodejs/nodejs_mysql.asp

https://www.npmjs.com/package/mysql

https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction
