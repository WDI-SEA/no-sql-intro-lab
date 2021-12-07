# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?
    * NoSQL databases are non-tabular(no tables) databases and store data differently than relational tables. NoSQL DBs have a variety of types based on their data model.  
    * Main types: Document, key-value, wide-column, and graph
    * Also known as nonrelational databases  
2. What are some of the common arguments for using a non-relational versus a relational db?
    * No investment to design model.
    * Rapid development cycles
    * In general faster than SQL
    * Runs well on the cloud  
3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db?
    * A document based db is composed of field and value pairs
    * Like a JSON file except its BSON(Binary JSON)
    * BSON extends JSON with additional data types, such as ObjectID and Date

4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?  
    * MongoDB automatically maintains replica sets, multiple copes of data that are distributed across servers, racks, and data centers. Replica sets help prevent database downtime using native replication and automatic failover
    * Replica set consists of multiple replica set members.  
5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 
    * Tables in SQL(pgAdmin4) would be accessed by going to the Schemas dir, then going into public, Tables, and then your users table should be residing within.
    * users in mongodb would be located in collections(table in SQL)  

6. What is an example situation where a Mongo database makes sense versus a relational db?
    * You want to use MongoDB over a relationalDB(SQL) when you need to store larger volumes of data without structure.
    * Using cloud computing and storage. Using affordable hardware on-site for tesitng and then for production in the cloud is what NoSQL databases are designed for.
    * Rapid development. Using modern agile methodologies, a relational database will slow you down. A NoSQL db doesn't require the level of preparation usually needed for relationalDBs

