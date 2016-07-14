1. download mysql installer and setup  
https://dev.mysql.com/downloads/windows/

2. use dos (mysql command line client) and login as root if required.

3. hit commands
show databases;  //to show databases

3. create database dbUser;

4. use dbUser;

5. Now create tables

create table user(
id int not null auto_increment,
name varchar(100),
pass varchar(100),
primary key(id)
);

6. show tables; //see tables on the selected database

7. insert into user values (1,"sandesh","lamsal");

8. select * from user;
