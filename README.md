# LoginRegisterApp

install MySQL version 8.0.21   (ie. 8.0.x)

database username: root
database password: admin

If you are using another user then needs to be changed in java file: DbUtil.java

mysql> create database tempdb;

mysql> use tempdb;

mysql> create table user(name varchar(100),password varchar(100), address varchar(1000), age int, profession varchar(100));

mysql> select * from User;
