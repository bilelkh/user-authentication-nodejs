# Nodejs User Authentication Sample #
A nodejs server api for user authentication
## Requirement ##
* [MongoDB](https://www.mongodb.com/) - Our Database
* [Expressjs](http://expressjs.com/zh-tw/) - API Server
* [Nodejs](https://nodejs.org/en/) - Backend Framework
* [NPM](https://www.npmjs.com/) - Package Management

## Install Nodejs dependence packages ##
>1. npm install
>2. node run.js 

This is simple demo of user authentication and account registration, use node js、express、mongodb to complete.

## packages ##

>1. [PassportJS](http://passportjs.org/) - for user password security
>2. [Simple JWT](https://www.npmjs.com/package/jwt-simple) - token use

## routing ##
* **api** - api root

* **api/users**

  ` post - create new user and password hash`


* **api/users/login**

	`post - login and get jwt token`

* **api/users/me**
	`get - get current user info`