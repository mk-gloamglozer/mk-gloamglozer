# Hi there,

Welcome to the github portfolio of Mike Davies PhD (almost...)

I'm currently working on expanding my portfolio and new projects will be added daily. 

My current area of expertise is **Java** and the **Spring** framework though I love front-end development too. Many of the projects within this repository are built in Java 
but I'm also well versed in **Python** and I'm hoping to upload a few examples in the next few days. Finally I'm actively learning **C#** and hope to be able to put together something similar
to the java projects in the near future. I've also made use of a couple of Javascript frameworks (React and Angular) in the past so making something with them is also on the list. 

## Repos
### OOP-demo
A demonstration of a number of OOP concepts as well as a basic IOC DI system. This project is the foundation of many of the other examples here being expanded 
in later iterations to include elements of the Spring framework as neccacarry. 

Once built (if you've got maven running it is easy with mvn exec::java), the program acts a very simple dice store, allowing the user to select dice to roll
and returning the result of rolling these dice via an interactive cli. Later iterations will improve what the user can do in terms of adding dice. 

JUnit5 and the mockito extension were used to create the unit tests for this program.

## spring-DI
This introduces the spring framework into the project to handle the dependancy injection and does away with the crude DI solution seen in OOP-demo.

## spring-JPA
In the original project the dice store is represented by an in memory object. Here this is replaced by the in memory H2 database using Spring-jpa and hibernate 
to enable persistant storage. 

## spring-Web [Coming Soon]
this project will expand the dice roller to accept REST based interaction

## booking-app
This one's my passion project and is as of yet unfinished. I hope to get a usable version soon. Developed with DDD principles in mind the vision of this 
project is to allow users to make bookings on so called 'Bookable' objects. These objects can be created and managed by users with a variety of security 
levels. It is backed by a database (currently H2) in which all objects are stored. 

Interaction with the program will be conducted via a RESTful interface. In time I intend to build a pretty front end in javascript. 

