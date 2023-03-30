# jasperReportDemo

This code is to demonstrate JasperReports in a brown bag session running on a Spring Boot webapp connected to a local MySQL database. To duplicate it the DB locally, please create the database according to the instructions below.

##To set up the MySQL Database:
mysql> create database db_example; -- Creates the new database
mysql> create user 'springuser'@'localhost' identified by 'ThePassword'; -- Creates the user
mysql> grant all on db_example.* to 'springuser'@'localhost'; -- Gives all privileges to the new user on the newly created database
