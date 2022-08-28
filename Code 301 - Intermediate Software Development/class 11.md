# Reading Notes

## To properly understand how the library operates and how to create web pages, I need to fully comprehend these phrases.

1.  	 
| SQL         | NoSQL       |
| :---        |    :----:   | 
|  primarily called as Relational Databases (RDBMS);   |  database are primarily called as non-relational or distributed database.       |
| not best fit for hierarchical data storage	    | fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data.        | 
| uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful	   | queries are focused on collection of documents. Sometimes it is also called as UnQL (Unstructured Query Language). The syntax of using UnQL varies from database to database.        | 
| are vertically scalable	   | are horizontally scalable| 
| either open-source or close-sourced from commercial vendors	   | can be classified on the basis of way of storing data as graph databases, key-value store databases, document store databases, column store database and XML databases.        | 
 	 
2. What kind of data is a good fit for an SQL database?
 > SQL databases are good fit for the complex query intensive environment.

3. Give a real world example: 
 > Replication: By replicating MySQL database across multiple nodes the work load can be reduced heavily increasing the scalability and availability of business application.

4. What kind of data is a good fit a NoSQL database?
 > NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data.

5. Give a real world example: 
 > All Web applications require user profiles and the ability to log in. A global user profile store is another example of where the key value characteristics
 >  of NoSQL come into play. A NoSQL database can store the user IDs, user preferences, multiple ID mappings and additional user information so that the app
 >   can quickly look up a user and authenticate access. Given the importance of this functionality to any Web app, the “always on” and scale-out characteristics
 >    of NoSQL are essential. TuneWiki recently drafted a blog post about how it uses NoSQL as a user profile store.

6. Which type of database is best for hierarchical data storage?
 > noSQL

7. Which type of database is best for scalability?
 > NoSQL 

8.What does SQL stand for?
 > Structured Query Language

9. What is a relational database?
 >  is a type of database that stores and provides access to data points that are related to one another.

10. What type of structure does a relational database work with?
 > tables 

11. What is a ‘schema’?
 > is like a skeletal structure representing a logical view of a whole database. It devises all the constraints applied to the data in a particular database. Whenever organizations engage in data modeling, it leads to a schema.

12. What is a NoSQL database?
  >  is an approach to database design that enables the storage and querying of data outside the traditional structures found in relational databases liks MongoDB
 
13. How does it work?
  > NoSQL databases store data in documents rather than relational tables. Accordingly, we classify them as "not only SQL" and subdivide them by a variety of 
  > flexible data models. Types of NoSQL databases include pure document databases, key-value stores, wide-column databases, and graph databases.

14. What is inside of a Mongo database?
  > MongoDB stores data records as documents (specifically BSON documents) which are gathered together in collections. A database stores one or more collections 
  > of documents.

15. Which is more flexible - SQL or MongoDB? and why
  > MongoDB because > The same collection can be used to contain both fresh data that you contribute and new data that you later want to fetch.

16. What is the disadvantage of a NoSQL database? 
  > Lack of Standardization:
  > There is no standard that defines rules and roles of NoSQL databases. The design and query languages of NoSQL databases vary widely between different
  >  NoSQL products – much more widely than they do among traditional SQL databases.
  >  Backup of Database:
  >  Backups are a drawback in NoSQL databases. Though some NoSQL databases like MongoDB provide some tools for backup, these tools are not mature 
  >  enough to ensure proper complete data backup solution.


## Things I want to know more about

