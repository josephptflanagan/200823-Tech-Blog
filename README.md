# 200823-Tech-Blog

## GitHub Repository
[Repository](https://github.com/josephptflanagan/200823-Tech-Blog)

## Heroku Site
[Heroku]()

### Description
A CMS-style tech blog similar to a wordpress site where developers can publish their blog posts and comment on other developers’ posts as well. Created to solidify ideas of ORM (Object Relational Mapping) and the MVC (Model-View-Controller) paradigm.

### Installation Instructions
* Download all files from repository
* use npm to install dotenv, create a .env file and populate it with:
* * DB_NAME='tech_blog_db'
* * DB_USER='your-MySQL-username'
* * DB_PW='your-MySQL-password'
* * SECRET='your-secret'
* use npm to install express, express-handlebars, express-session, connect-session-sequelize, mysql2, sequelize, bcrpyt, jest (to use test functionality)
* initialze database on MySQL server using schema file
* start server with 'npm start' and view the result with 'localhost:3001'
