# JasperReports Demo

This code is to demonstrate JasperReports in an ACN brown bag session running on a Spring Boot webapp connected to a local MySQL database. To duplicate it the DB locally, please create the database according to the instructions below.

## Requirements
MySQL version 5.6 or better. If you have Docker installed, it might be useful to run the database as a container.

 - About 15 minutes
 - A favorite text editor or IDE (I used Eclipse v.4.27)
 - Java 17 or later
 - Gradle 7.5+ or Maven 3.5+


## To set up the MySQL Database:
The database was set up based on instructions found [in this Spring Boot guide](https://spring.io/guides/gs/accessing-data-mysql/).
```
mysql> create database db_example; -- Creates the new database
mysql> create user 'springuser'@'localhost' identified by 'ThePassword'; -- Creates the user
mysql> grant all on db_example.* to 'springuser'@'localhost'; -- Gives all privileges to the new user on the newly created database
```
## To set up Jasper
- Step 1 placeholder
- Step 2
