CREATE DATABASE library; 
USE library;
CREATE TABLE authors (
AuthorID INT NOT NULL, 
AuthorFirstName VARCHAR(20) NOT NULL, 
AuthorLastName VARCHAR(20) NOT NULL, 
AuthorNationality VARCHAR(20)NOT NULL,
PRIMARY KEY (AuthorID)
);

CREATE TABLE books (
BookID INT NOT NULL,
BookTitle VARCHAR(50) NOT NULL,
AuthorID INT NOT NULL,
Genre VARCHAR(25) NOT NULL
PRIMARY KEY (BookID)
FOREIGN KEY (AuthorID) REFERENCES Authors(AuthorID)
);

CREATE TABLE borrowers (
BorrowID INT NOT NULL,
ClientID INT NOT NULL,
BookID INT NOT NULL,
BorrowDate 
PRIMARY KEY (BorrowID)
FOREIGN KEY (ClientID) REFERENCES Clients(ClientID)
FOREIGN KEY (BookID) REFERENCES Books(BookID)

CREATE TABLE clients (
ClientID INT NOT NULL,
ClientFirstName VARCHAR(25) NOT NULL,
ClientLastName VARCHAR(25) NOT NULL,
ClientDoB YEAR,
Occupation VARCHAR(50) NOT NULL
PRIMARY KEY (ClientID)
);
