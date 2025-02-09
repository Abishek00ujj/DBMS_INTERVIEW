# DBMS Interview Questions with Answers

## 1. What is DBMS?
- A **Database Management System (DBMS)** is software that interacts with users, applications, and databases to capture and analyze data. Examples: MySQL, PostgreSQL, Oracle.

## 2. What are the types of DBMS?
- **Hierarchical DBMS**
- **Network DBMS**
- **Relational DBMS (RDBMS)** (most widely used)
- **Object-oriented DBMS**

## 3. What is the difference between DBMS and RDBMS?
- **DBMS** manages databases, while **RDBMS** enforces relationships among tables using primary and foreign keys.

## 4. What are the ACID properties?
- **Atomicity**: Ensures complete transactions.
- **Consistency**: Ensures valid data.
- **Isolation**: Prevents transactions from interfering.
- **Durability**: Ensures permanent changes.

## 5. What is normalization? Why is it needed?
- **Normalization** organizes data to eliminate redundancy and improve integrity.
- **Forms**: 1NF, 2NF, 3NF, BCNF, etc.

## 6. What is denormalization?
- **Denormalization** improves performance by reducing joins and increasing redundancy.

## 7. What is a primary key?
- A **primary key** uniquely identifies a record in a table.

## 8. What is a foreign key?
- A **foreign key** is a field in one table that refers to a primary key in another table.

## 9. What is indexing in DBMS?
- **Indexing** improves the speed of data retrieval operations.

## 10. What are different types of indexes?
- **Primary Index**
- **Clustered Index**
- **Non-clustered Index**
- **Unique Index**

## 11. What is a view in DBMS?
- A **view** is a virtual table based on a query.

## 12. What is a stored procedure?
- A **stored procedure** is a set of SQL statements stored in the database.

## 13. What is a trigger in DBMS?
- A **trigger** is an automatic action executed in response to an event in the database.

## 14. What are transactions in DBMS?
- A **transaction** is a sequence of operations performed as a single unit.

## 15. What is the difference between DELETE and TRUNCATE?
- **DELETE** removes specific rows and can be rolled back.
- **TRUNCATE** removes all rows and cannot be rolled back.

## 16. What is the difference between WHERE and HAVING?
- **WHERE** filters rows before aggregation.
- **HAVING** filters aggregated results.

## 17. What is the difference between UNION and UNION ALL?
- **UNION** removes duplicates.
- **UNION ALL** includes duplicates.

## 18. What is the difference between INNER JOIN and OUTER JOIN?
- **INNER JOIN** returns matching rows from both tables.
- **OUTER JOIN** returns all records, including non-matching ones.

## 19. What is a self-join?
- A **self-join** joins a table with itself.

## 20. What is a cursor in DBMS?
- A **cursor** is used to iterate over query results row by row.

## 21. What is the difference between clustered and non-clustered indexes?
- **Clustered Index**: Physically sorts table data.
- **Non-clustered Index**: Stores pointers to data.

## 22. What is the difference between CHAR and VARCHAR?
- **CHAR**: Fixed-length storage.
- **VARCHAR**: Variable-length storage.

## 23. What are aggregate functions in SQL?
- **COUNT, SUM, AVG, MIN, MAX**.

## 24. What are constraints in DBMS?
- **Constraints** enforce rules (e.g., NOT NULL, UNIQUE, PRIMARY KEY).

## 25. What is the difference between OLAP and OLTP?
- **OLAP (Online Analytical Processing)**: Data analysis, reporting.
- **OLTP (Online Transaction Processing)**: Day-to-day transactions.

## 26. What is deadlock in DBMS?
- A **deadlock** occurs when two transactions hold resources the other needs.

## 27. What is the difference between a database and a data warehouse?
- **Database**: Stores operational data.
- **Data Warehouse**: Stores historical data for analysis.

## 28. What is an ER model?
- The **Entity-Relationship Model** represents real-world data as entities, attributes, and relationships.

## 29. What is the difference between a weak and strong entity?
- **Strong Entity**: Has a primary key.
- **Weak Entity**: Depends on a strong entity (uses a foreign key).

## 30. What is BCNF (Boyce-Codd Normal Form)?
- **BCNF** eliminates redundancy by ensuring every determinant is a candidate key.

## 31. What are ACID properties used for?
- ACID ensures reliable transactions in a database.

## 32. What is sharding in DBMS?
- **Sharding** partitions data across multiple databases for scalability.

## 33. What is NoSQL? How is it different from SQL?
- **NoSQL** databases store unstructured data, unlike **SQL** (structured tables).

## 34. What are different types of NoSQL databases?
- **Key-Value Store** (Redis), **Document Store** (MongoDB), **Column Store** (Cassandra), **Graph DB** (Neo4j).

## 35. What is CAP theorem?
- **CAP** states that a distributed database can only ensure two of **Consistency, Availability, Partition Tolerance** at a time.

## 36. What is normalization anomaly?
- **Anomalies** occur due to data redundancy, solved via normalization.

## 37. What is an index scan vs. a table scan?
- **Index Scan** uses an index.
- **Table Scan** reads all rows sequentially.

## 38. What is an execution plan in SQL?
- **Execution Plan** shows how a query is processed by the database engine.

## 39. What is the difference between SAVEPOINT and ROLLBACK?
- **SAVEPOINT** creates a partial rollback point.
- **ROLLBACK** undoes transactions.

## 40. What is the difference between logical and physical data independence?
- **Logical**: Change schema without affecting applications.
- **Physical**: Change storage without affecting schema.

## 41. What is a materialized view?
- A **materialized view** stores query results for fast access.

## 42. What is surrogate key vs natural key?
- **Surrogate Key**: Auto-generated.
- **Natural Key**: Derived from business logic.

## 43. What is a B-Tree index?
- **B-Tree index** speeds up queries using a balanced tree structure.

## 44. What is partitioning in databases?
- **Partitioning** splits tables for improved performance.

## 45. What is a phantom read in DBMS?
- **Phantom Read** occurs when new records appear during a transaction.

## 46. What is difference between 2PL and MVCC?
- **2PL (Two-Phase Locking)**: Prevents conflicts using locks.
- **MVCC (Multi-Version Concurrency Control)**: Uses snapshot-based isolation.

## 47. What is replication in DBMS?
- **Replication** copies data across multiple servers for redundancy.

## 48. What is difference between soft delete and hard delete?
- **Soft Delete** marks records as deleted.
- **Hard Delete** removes records permanently.

## 49. What is difference between Star and Snowflake schema?
- **Star Schema**: Simple, fewer joins.
- **Snowflake Schema**: More normalization, complex joins.

## 50. What is a checkpoint in DBMS?
- **Checkpoint** saves database state to recover from failures faster.

---

Let me know if you need modifications or additional topics! 🚀

