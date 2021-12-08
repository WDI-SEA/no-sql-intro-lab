# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL? <br>

      noSQL refers to a database that does not use a structured query language. These databases are also referred to as 'non-realational' databases.
      
      
  <br>  
2. What are some of the common arguments for using a non-relational versus a relational db?<br>


  Non-realtional db's are easier to scale quickly and re-structure. If you are building out a database for a new application in the early development stages, and realize you need to add a new kind of data and relation to your db, non-relational db's are much easier to update and manipulate while maintaining all of the existing data. Basically, they can make the development process faster and more efficient.
  <br>
  <br>
  
  
3.In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db?<br> 


  Document based db's are comrpised of BSON (Binary JavaScript Object Notation) objects, which are referred to as documents. This allows developers to write queries in the familiar dot notation used for accessing JavaScript objects.
  <br>
  
  
4 In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamy difference between how Mongo is maintained vrs SQL?<br>


  SQL databases can only be stored on one server, which limits scalability. Mongo databases can be 'sharded' and be stored across many servers, removing barriers to horizontal scaling.
  <br>
  
  
5.Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo.<br>


  A table of users in SQL would have a fixed number of fields for each user, such as 'id', 'name', and 'age'. Every user would have the field 'age', even if there is no age stored for that user. In a Mongo db the 'age' field only needs to be added to a user when and age is sent to the database to be stored.
  <br>
  
  
6. What is an example situation where a Mongo database makes sense versus a relational db?<br>


  Social networks greatly benefit from Mongo databases versus relational databases becuase of their scalability and flexibility. Where the rigidity of SQL would benefit a bank to keep data secure and and unchanging, a social network couuld use a MongoDB's flexibility to continually store new kinds of data for every user when offering new features. Because social networking applications can become popular very quickly, MongoDB's allow them to scale their data structures to meet spikes in demand with little costs, where a SQL application would have to invest more money in infrastructure to keep up with demand, and at a necessarily slower rate.
