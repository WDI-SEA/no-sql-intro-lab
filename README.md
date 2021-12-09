# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?

    * NoSQL refers to non-relational databases.

2. What are some of the common arguments for using a non-relational versus a relational db?

    * It allows you much more flexibility to add data. Also, it doesn't require you to use any join tables. It can also hold large amounts of imformation. 

3. In this class we will be using the document style of non-relational databases. What are the characteristics of a document based db? 

    * Document based dbs have collections, documents, and fields. It also uses BSON objects.

4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the primary difference between how Mongo is maintained vs SQL?

    * NoSQL databases are much less rigid and require less maintenance and training. 

5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 

    * SQL uses tables with columns and rows that hold determined fields of info about users (name, email, age, etc.). Mongo stores information using field/value pairs. Mongo is far more flexible with updating/adding information. 

6. What is an example situation where a Mongo database makes sense versus a relational db?

    * Any kind of social media where there are many requests being made, makes more sense with Mongodb. 
