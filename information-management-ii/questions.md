---
title: Information Management II Questions
author: by Ultan
---

 

Introduction
------------

 

Some questions from, or relevant to, the course.

 

Questions
---------

 

**Theory**

 

-   List three advantages of a database

-   What are data definition, modification, query and control languages? What is
    SQL?

-   What are the three levels of a database architecture?

-   What are relations, tuples and attributes?

-   What is the domain?

-   What is the degree?

-   Is the value in a tuple atomic?

-   What is a null value?

-   What is a primary key?

-   What is an entity integrity constraint? What is referential integrity?

-   What is a foreign key?

-   Give an example of selection, projection and combining in SQL

-   List the SQL set operations. How would you include duplicates?

-   What is a join in SQL?

-   What are the the requirements for a normalised table?

-   What is a determinant? Explain giving an example

-   What is a composite attribute?

-   What does a determinant diagram look like?

-   What is Codd Normal Form?

-   What is an identifier?

-   What is a candidate key?

-   What is Boyce/Codd Normal Form?

-   What is a fully normalised table?

-   Give an example entity relationship diagram

-   Give an example entity relationship diagram with relationships that have
    roles, recursiveness, constraints (cardinality) and constraints
    (participation)

-   Map your entity relationship diagram to a relational schema

-   What are the four design optimisation guidelines?

-   How can you disprove a functional dependency?

-   How can you specify in a schema that a functional dependency should hold?

-   List the four steps for modelling a database

-   What is the super key?

-   Are integrity constraints concerned with accidental corruption?

-   Are explicit constraints expressed in the relational schema?

-   Can semantic constraints be expressed in the relational schema?

-   What are the integrity constraints? What are they in SQL?

-   Can foreign keys be null?

-   List constraint violations possible for key, entity and referential. How can
    these violations be handled? What are they in SQL?

-   What does cascading mean?

-   What are the constraints for?

    -   PRIMARY KEY

    -   FOREIGN KEY

    -   UNIQUE

    -   NOT NULL

    -   CHECK

    -   ASSERTION

    -   TRIGGER

-   Explain security with reference to accounts, privileges and security levels

-   What is a transaction? What is concurrency control?

-   Contrast SQL to NOSQL

-   What is sharding? What is replication?

-   What is the CAP theorem?

-   What is ACID? What is BASE?

-   List four NoSQL data models?

-   What is the data model and the storage model?

 

**SQL**

 

These questions assume you have a suitable database with some schemas created
already.

 

*Question 1*

-   Using the appropriate SQL command, update your contact table to include a
    contact type

-   How would the database ensure that the contact is of an appropriate type?
    For example, only work colleagues could be added to a work conversation

 

*Question 2*

-   One of the users in the database has decided to change their name; update
    the name of the user to reflect this change

 

*Question 3*

-   Retrieve all of the conversations that, “Jared Dunn” was a participant in
    during 2017

 

*Question 4*

-   Write a retrieval command which returns all video chat sessions which have
    more than ten participants

 

*Question 5*

-   What adjustments would have to be made to link the player table and the team
    table? Demonstrate using SQL

 

*Question 6*

-   Using the appropriate SQL command, demonstrate how the database ensures that
    both players in a battle are of the appropriate level

 

*Question 7*

-   How do you handle referential integrity?

 

*Question 8*

-   Create a supplier table that is used to store entries for each of Pablo’s
    suppliers. The table should have a “type” attribute, which should always
    have one of the following values, “farmer”, “chemical” or “equipment”

 

*Question 9*

-   Write a retrieval command which returns a list of customer names and a total
    value of all the purchases that that customer has made

 

 
