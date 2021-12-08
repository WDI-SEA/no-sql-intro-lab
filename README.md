# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?
    * noSQL databases, also referred to as non-relational databases, are non-tabular databases that store data differently than relational tables. 
    * They come in a variety of types based on the data model and store data in a format other than relational tables.

2. What are some of the common arguments for using a non-relational versus a relational db?
    * No joins are required which results in faster queries
    * Flexibility of the schema 
    * Scaling technique
    * Support for transactions
    * Reliance on data to object mapping

3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 
    * Four major types of NoSQL databases emerged over time: document databases, key-value databases, wide-column stores, and graph databases.
    * Document databases store data in documents similar to JSON (JavaScript Object Notation) objects. Each document contains pairs of fields and values. The values can typically be a variety of types including things like strings, numbers, booleans, arrays, or objects.

4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?
    * Doesn't require join tables, doesn't need to have data structured like SQL, and saves data in BSON/JSON format.

5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 
    * SQL has information in a table stored in rows and columns whereas Mongo has a field of data stored as a BSON/JSON object (a document). 

6. What is an example situation where a Mongo database makes sense versus a relational db?
    * Mongo makes more sense in any of the following situations: 
        * Fast-paced Agile development
        * Storage of structured and semi-structured data
        * Huge volumes of data
        * Requirements for scale-out architecture
        * Modern application paradigms like microservices and real-time streaming