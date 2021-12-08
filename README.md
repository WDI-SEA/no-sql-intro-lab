# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?
The term noSQL refers to any non-relational database. NoSQL also refers to “not only SQL” or “non-SQL”.
2. What are some of the common arguments for using a non-relational versus a relational db?
Some benefits of using a non-relational database include:
* scalability and speed
* can store new data even if it doesn't fit the data types of previously existing information
* can collate different information types together in the same document
* built for the cloud
3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 
Data is stored in individual pages or documents.
4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?
Mongo is maintained by a publicly traded company whereas SQL is a querying language. 
5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo.

User table using SQL
id	username	password	email
1	dummyuser	12345678	dummy@domain.com

User table using MongoDB
{   "_id": ObjectId("xxxxxxxxxxxxxxxxxxxx"),
    "user": "dummyuser",
    "password": "12345678",
    "email": "dummy@domain.com"
}

6. What is an example situation where a Mongo database makes sense versus a non-relational db?
Mongo doesn't require a database administrator. It is user-friendly and can be used by both developers and administrators.
