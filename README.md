CREATE DATABASE bt20052024
USE bt20052024

CREATE TABlE products(
 id BIGINT,
 name VARCHAR(255),
 description VARCHAR(255),
 price FLOAT,
 PRIMARY KEY(`id`)
);

CREATE TABLE students(
	id BIGINT,
	name VARCHAR(255),
	email VARCHAR(50),
	dob DATETIME,
 	PRIMARY KEY(`id`)
	
);

DROP TABLE products 
DROP TABLE students 
