# Php_Script_For_Transaction
A classy script for bank transactions in localhost.

We will create a table name accounts to transfer money between two banks..

First execute the following steps to create the accounts table :
CREATE TABLE accounts (
  id int(11) NOT NULL AUTO_INCREMENT,
  name varchar(50) NOT NULL,
  amount decimal(19,4) DEFAULT NULL,
  PRIMARY KEY (id)
) ENGINE=InnoDB;
