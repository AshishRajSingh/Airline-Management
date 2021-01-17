# Airline-Management-System.
Airline Management System.
AIRLINE MANAGEMENT SYSTEM
JAVA Core Project

This project on Airline Management System is the automation of registration process of airline system. The system is able to provide much information like passenger’s information, criminal’s, list of all passengers etc. The system also allows us to add records when a passenger reserves a ticket. For data storage and retrieval we use MySQL Database. It enables us to add any number of records in our database. 

Language Used -  Java Core 
Concept Used - Swing
IDE Used - NetBeans
Database Used - MySQL
https://drive.google.com/file/d/1flYQG5eCAn1aIi49xep78kquQw0Et14x/view?usp=sharing

Database
1 - Create table with name cancellation

create table cancellation(pnr_no varchar(10), cancellation_no varchar(10), cancellation_date DATE, fli_code varchar(15));

2 -  create table with name flight

create table flight(f_code varchar(10), f_name varchar(20), src varchar(30), dst varchar(30));

3 - create table with name login

create table login(username varchar(20), password varchar(20));

4 - create table with name passenger

create table passenger(pnr_no varchar(10), address varchar(30), nationality varchar(15), name varchar(20), gender varchar(10), ph_no varchar(15), passport_no varchar(20), fl_code varchar(10));

5 - create table with name payment

create table payment(pnr_no varchar(10), ph_no varchar(15), cheque_no varchar(15), card_no varchar(20), paid_amt varchar(10), pay_date DATE);

6 - create table with name reservation

create table reservation(pnr_no varchar(10), ticket_id varchar(10), f_code varchar(10), jny_date DATE, jny_time varchar(10), src varchar(20), dst varchar(20));

7 - create table with name sector

create table sector(flight_code varchar(20), capacity varchar(10), class_code varchar(5), class_name varchar(20));


