# NOSQL

NoSQL refers to "Not Only SQL" because in SQL or RDBMS, the data is stored in a predefined format, making it difficult to add new elements for specific users or add new data further. For example, only predefined data variables like [name, id, number, address] are allowed. If new data like an image needs to be added only to a specific user, it is not possible without adding another column 'image' in the database.
## Why Nosql?
In the above case, with the help of a NoSQL-type database, we can store any info at any point in time because there are no predefined variables to restrict. If an image needs to be added or a new address needs to be added to a specific user (not for remaining users), it could be possible in NoSQL.In SQL the column image is added to all the users, there is only one standard way of storing data columns and variables but in NoSQL, there are many ways to store the data. where the user could choose based on their preferences.  Below are a few examples of NoSQL databases:

## Types:
Unlike SQL, there are many types of NoSQL, which we can choose based on requirements. There are 4 widely used databases: Document, Key-value, Column, and Graph.

### Document type:
These types of databases store data in the form of Documents like JSON, XML, or BSON formats. MongoDB and Couchbase are some widely used document databases.

### Key-Value Stores:
Here, data is stored in a key-value pair, where each key is unique and associated with a value. These databases are highly scalable and efficient for simple retrieval operations. Amazon DynamoDB is an example of a key-value type database.

### Column-Family Stores:
Here, the data is stored in long columns as key-value keys in row 1 and values in 2. These are more suitable for analyzing and processing. Apache Cassandra is a widely used Column type database.

### Graph Databases:
The data is stored in the form of nodes like a graph data structure format. This kind of DB is mostly used for mapping and querying data with complex relations. Neo4j is considered the best example of a graph type of database.

## References:
- MongoDB: https://www.mongodb.com/
- Couchbase: https://www.couchbase.com/
- Amazon DynamoDB: https://aws.amazon.com/dynamodb/
- Apache Cassandra: https://cassandra.apache.org/_/index.html
- Neo4j: https://neo4j.com/m/
