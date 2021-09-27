# SQL
 - Structured Query Language (language that allows you to write database queries)
 - certain syntax and keywords combined with  data parameter -- retrieving data, inserting, updating, deleting data from tables

# SQL Database
- **Relational database** - a database that works with certain assumptions
- Based on tables (a storage container/data bin)
- There are strict requirments about the data that is stored - a schema about which data can go into which table - the schema is defined by fields (id, name, date are a few common types) - **each record added to the table must follow the schema and its defined fields**
- Data must be normalized - whatever data we bring in to fill the schema requirments, must adapted into a format that fits the table
- Most likely are working with more than one table (A user table data is pulled and merged with data pulled from a product table to create an orders table)
- Can struggle when large amounts of data

# NoSQL
- Based on my basic knowledge of MonogDB
- There is a database, that is divided into collections, and each collection holds documents
- No schema in the documents, so each document in the collection can be formatted differentlyy
- **Pros - it allows for flexibility - Pros - efficient querying because data is in one place**
- **Cons: may not be sure if the data being retrieved meets formatting requirments, but that would be coded for -- Cons - duplication of data (if data changes then it would need to be updated in multiple collections (this would be a great setup if the app has more data reads than data writes)
- No relations (it is possible to relate multiple collections) - instead the idea id that all information is put in one place (so to create a orders collection, you would bring in all the key info from the users collection and the products collections) - you would not need to query the users data or the products data separately because all the data that is needed is in one place
- 
