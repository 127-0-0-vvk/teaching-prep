# Azure Databases

## Cosmos DB

### Questions

| Can Answer? | # | Question |
| --- | --- | --- |
| <input type="checkbox"> | 1 | What is Cosmos DB? |
| <input type="checkbox"> | 2 | What does global replication for Cosmos DB mean? |
| <input type="checkbox"> | 3 | What is JSON? |
| <input type="checkbox"> | 4 | What APIs does Cosmos DB provide? |

### Answers

1)Cosmos DB is a globally distributed, multi-model, NoSQL database service provided by Microsoft Azure. It supports various data models like document, key-value, graph, and column-family, making it suitable for a wide range of applications.


2)Global replication in Cosmos DB means that data is automatically replicated and synchronized across multiple Azure regions worldwide. This ensures low-latency access to data for users in different geographic locations and provides high availability and disaster recovery capabilities.


3)JSON (JavaScript Object Notation) is a lightweight data interchange format. It is easy for humans to read and write and easy for machines to parse and generate. JSON is commonly used for representing and exchanging structured data.


4)Cosmos DB provides various APIs to interact with the data models it supports:

Core (SQL) API: Compatible with MongoDB and provides SQL-like query capabilities.
Table API: Provides key-value data model with table semantics.
Cassandra API: Compatible with Apache Cassandra and offers column-family data model.
Gremlin API: Supports graph data model and provides graph-based querying with Apache TinkerPop Gremlin.
MongoDB API: Compatible with MongoDB and offers support for document data model.

### Exercises

| Done? | # | Exercise |
| --- | --- | --- |
| <input type="checkbox"> | 1 | Create a Cosmos DB NoSQL Account. |
| <input type="checkbox"> | 2 | Create a Database and a Container in your account. |
| <input type="checkbox"> | 3 | Insert and Retrieve some records from your NoSQL container. |

## Azure SQL

### Questions

| Can Answer? | # | Question |
| --- | --- | --- |
| <input type="checkbox"> | 1 | When database is called a relational database? |
| <input type="checkbox"> | 2 | What is an Elastic Pool for Azure SQL? Why use it? |
| <input type="checkbox"> | 3 | What is an Azure SQL Managed Instance? Why use it? |
| <input type="checkbox"> | 4 | What is the relationship between Azure SQL Server and Azure SQL database? |

### Answers 


1)A database is called a relational database when it follows the principles of the relational model. It stores data in tables with rows and columns, and the relationships between tables are established using foreign keys.


2)An Elastic Pool is a collection of Azure SQL Databases with a shared set of resources. It allows you to pool together databases with varying and unpredictable workloads, enabling efficient resource utilization and cost savings.


3)Azure SQL Managed Instance is a fully-managed SQL Server instance hosted in Azure. It provides nearly 100% compatibility with on-premises SQL Server and allows lift-and-shift migration of existing applications without requiring changes.


4)Azure SQL Database is a managed service that provides a fully-managed database platform, whereas Azure SQL Server refers to a virtual machine running SQL Server in the Azure cloud.


## Azure Database for MySQL

### Questions

| Can Answer? | # | Question |
| --- | --- | --- |
| <input type="checkbox"> | 1 | What can you tell us about Azure Database for MySQL? |

### Answers 


1)Azure Database for MySQL is a fully-managed database service that provides a MySQL database engine in the Azure cloud. It handles database management tasks like backups, patching, and scaling, allowing developers to focus on application development.

## Azure Database for PostgreSQL

### Questions

| Can Answer? | # | Question |
| --- | --- | --- |
| <input type="checkbox"> | 1 | What can you tell us about Azure Database for PostgreSQL ? |

### Answers 

1)Azure Database for PostgreSQL is a fully-managed database service that provides a PostgreSQL database engine in the Azure cloud. It offers high availability, automated backups, and scaling capabilities.

## Azure Database Migration Service (DMS)

### Questions

| Can Answer? | # | Question |
| --- | --- | --- |
| <input type="checkbox"> | 1 | What is Azure DMS used for? |

### Answers 

1)Azure Database Migration Service is used for migrating on-premises databases to Azure. It simplifies the process of database migration by providing a guided experience and minimizing downtime during the migration process.

