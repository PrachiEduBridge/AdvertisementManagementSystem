# AdvertisementManagementSystem

 




A Project Report On
Advertisement Management System
By
Prachi Rewatkar B.Tech
Batch: - 2020 – 4970
Center:- Thane Mumbai


Under the Guidance of,
Jayant V.
Technical Trainer



EduBridge
(School of coding)
 



Introduction:

Advertisement management system project is a complete online solution for advertisers who want to advertise their product on online media or websites. Advertisement Management System project is developed using ASP.NET and SQL server. This project is developed for the users who want to manage their online advertisement from one place. This website is very helpful to advertisement agency staffs and managers to manage advertisements and to view reports.
This project report gives overall system information of the system. Here you can get DFD and ER diagram of the advertisement management system. In this project report we have also explained the different module of advertisement management system. This project report can be used for system design, system development and system testing. It provides information for understanding the system.
An advertiser is the person who wants to display their ads online.
Ad Agency
Ad Agency module are independent Ads Agencies those helps advertiser to make their ads content and are connected with the advertisement management system
 Customers
Customers are the Publisher Websites those are connected with the advertisement system and  where advertisement will be displayed
Use can make their advertisement with himself or he can also take helps of advertisement agency to create ads. After creating ads user can select any Customers from list. Then user select any available plan for advertisement. After completing the payment users ads will be displayed on Customers website. User can add as many Customers as he want from the list.








Software Requirements:

Front end:	Java/J2EE technologies (Servlet, JSP), HTML,
CSS, JDBC.

Back end:	MySQL. Middleware/Server:	Apache Tomcat v9.0.
IDE:	Eclipse IDE for Java EE Developers

Browser:	Best result on Google Chrome Operating System:	Window XP (Minimum).

ERD (Entity Relationship Diagram):


  
 


Data Dictionary:


create database adpoint;

Table name: consumer
create table customer(name varchar(10), email varchar(25), password varchar(25), mobile varchar(10), city varchar(10));

Table name: agency
create table agency(name varchar(10), email varchar(25), password varchar(25), mobile varchar(10), city varchar(10));

insert into consumer values(nikita,'nikita.pr@gmail.com','ganeshji@8','9476286455','nagpur');
insert into agency values(DTRU,'DTRU.pratikHR@gmail.com','ganu@6754','9578254933','mumbai');











Screenshots :-
Home Page:-
 


  
ConsumerHomePage :-
 
ConsumerLoginForm:-

 

Customer Sign up:-
 

AD Agency home:-
 
  AD Agency Login:-
 
AD Agency Signup:-

 
 
 About us:-
 




Contact us:-

  
Objective
Now a day’s people are purchasing products online. Therefore, it is necessary for the company to advertise their product online. Online advertising is a very complicated task we need a system to manage it. Advertisement management system helps to manage online advertising. This system provides the complete service for advertiser to introduce their products and services into online market. Advertisement management system will give the solution of all problems that comes in online marketing. In this system user can create ads and can also select website where he want to show their ads online.
Advertisement system has following plans for users
3 month
6 month
1 year
System will provide the list of subscriber websites for user. System will provide login and profile facility for user where advertisement can be added or deleted or updated. Advertisement management system will make use of online payment system for receiving payment from user. User Manual will be provided for user help.
System design
3.1. Modules
These are the modules (Web Page) used in AMS.
Home
Home page is the first page of the website. When user go the website of advertisement management system this is the first page that will display to user.
Following links are displayed on home page.
Home
Login
Sign up
About us
Contact us
