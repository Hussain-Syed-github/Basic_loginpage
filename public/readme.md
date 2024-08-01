
# Prerequisites
#### Install Node.js and npm (Node Package Manager) from nodejs.org.
#### Install MySQL and MySQL Workbench for database management.
## Create a Project Directory:
mkdir login_page\
cd login_page
## Initialize a Node.js Project:
npm init -y
### Install Required Packages used in the server.js file
## Set Up MySQL Database
### Create a Database and Table:
CREATE DATABASE login;

USE login;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(255) NOT NULL,
    password VARCHAR(255) NOT NULL
);



