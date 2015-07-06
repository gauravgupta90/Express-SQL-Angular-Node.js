Sample App to demostrate working with Express framework, SQL(orm module), Angular, Node.js
==========================================================================================

The purpose of this app is to querry the daily views and give demostration to work with orm module, Express framework, Angular.js.

### Install an app

Run the following command in 'root' directory of an app in command prompt.

###### *Install node packages*

npm install

### Create Database

CREATE TABLE 'test'.'views' (

  'id' INT NOT NULL AUTO_INCREMENT,

  'username' VARCHAR(45) NOT NULL,

  'count' VARCHAR(45) NOT NULL,

  'date' DATE NOT NULL,

  PRIMARY KEY ('id'));

### Run an app

###### *Run Server*

Run the following command in 'root' directory of an app in command prompt.

node server.js

You can see the port number in command prompt after sucessfull run

###### *App Configuration*

Inside config/config.js

db: You can change username, password, hostname and database name. "mysql://username:password@hostname/database"

port: port number

cronTime: SS MM HH * * *

timeZone: any valid time zone

apiKey: apiKey

![Screenshot](./screenshot.PNG?raw=true )

### Other Usefull Link

[Hapi-Mongoose-Angular-Node.js] (https://github.com/gauravgupta90/Hapi-Mongoose-Angular-Node.js)

[Passport-Auth-Hapi.js-Mongoose] (https://github.com/gauravgupta90/Passport-Auth-Hapi.js-Mongoose)

[Token-Based-Auth-With-User-Roles-Hapi-Mongoose-Mongodb-with-email-verification-and-forgot-password] (https://github.com/gauravgupta90/Token-based-Auth-with-user-role-in-Hapi-Mongoose-Mongodb-with-email-verification-and-forgot-password)

