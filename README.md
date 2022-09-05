<img src="https://github.com/Oleksii-Mospan/movie-service-app/blob/main/src/main/resources/logo.png?raw=true" alt="Logo of the project" align="right">

# Movie Service &middot;
[![version](https://img.shields.io/badge/version-1.0.0-yellowgreen.svg)](https://semver.org)

This is a service used for order tickets to the movie.

## This service has several services:
### AuthenticationService
Authentication of users (login and register)
### CinemaHallService
Adding and getting cinema halls
### MovieService
Adding and getting movies
### MovieSessionService
Adding, getting and find available movie sessions
### OrderService
Completing orders and getting order history
### ShoppingCartService
Adding and cleaning shopping cart
### UserService
Adding new users or find users by email.

## What this service uses
Service is build using Hibernate ORM

## For what this service can be used
1) For educational purpose
2) For adding in you project
3) For my personal educational purpose :)

# Configure service
Before using this service the schema of must be created in DB!

### To configure connection to database fill free to edit hibernate.cfg.xml 
(src/main/resources/hibernate.cfg.xml)

```XML
        <property name="connection.url"><!--URL_to_DB--></property>
        <property name="connection.username"><!--USERNAME--></property>
        <property name="connection.password"><!--PASSWORD--></property>
```
#### where:
- URL_to_DB - URL to Database
- USERNAME - username to get permission to read and write to database
- PASSWORD - password for USERNAME user

# Database
In this project we use MySQL database.

### Model structure
![pic](https://github.com/Oleksii-Mospan/movie-service-app/blob/main/src/main/resources/db.png)

