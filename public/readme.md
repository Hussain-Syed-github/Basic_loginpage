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
CREATE DATABASE loginapp;

USE loginapp;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(255) NOT NULL,
    password VARCHAR(255) NOT NULL
);
### Insert data into the Table
Insert the data of the users:\
Ex:\
INSERT INTO `login`.`users` (`id`, `username`, `password`) VALUES ('5', 'hussain', 'syed');\



