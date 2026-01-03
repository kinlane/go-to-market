---
title: Java Database Connectivity (JDBC)
description: JDBC (Java Database Connectivity) is a Java API that provides a standard interface for Java applications to connect to and interact with relational databases, allowing developers to execute SQL queries, retrieve results, and manage database transactions in a database-agnostic way.
date: 2025-12-31
weight: 70
toc_hide: true
---

{{% pageinfo %}}
Lighter weight data serialization format for data exchange.
{{% /pageinfo %}}

JDBC (Java Database Connectivity) is a Java API specification developed by Sun Microsystems (now Oracle) that provides a standard, database-independent interface for Java applications to interact with relational databases. Released as part of the Java platform, JDBC abstracts the complexities of database communication by defining a consistent set of interfaces and classes that allow developers to connect to databases, execute SQL statements, retrieve and process query results, and manage transactions without worrying about the underlying database vendor's specific implementation details. JDBC works through database-specific drivers that implement the JDBC interfaces—these drivers translate the standard JDBC calls into the native protocol of the particular database system (such as Oracle, MySQL, PostgreSQL, SQL Server, or DB2). This driver-based architecture enables developers to write portable database code that can switch between different database systems by simply changing the JDBC driver and connection string, rather than rewriting the entire data access layer.

JDBC provides several core components that work together to facilitate database operations: the DriverManager class for establishing connections, Connection objects that represent active database sessions, Statement and PreparedStatement objects for executing SQL queries and updates, ResultSet objects for iterating through query results, and various metadata classes for discovering database and result set structure at runtime. The API supports both simple statement execution and more advanced features like prepared statements with parameter binding (which prevent SQL injection attacks and improve performance through query plan caching), callable statements for executing stored procedures, batch processing for efficient bulk operations, transaction management with commit and rollback capabilities, and connection pooling for optimal resource utilization in multi-threaded applications. JDBC has become the foundation for higher-level data access frameworks like Hibernate, JPA (Java Persistence API), Spring JDBC, MyBatis, and jOOQ, which build upon JDBC's low-level capabilities to provide object-relational mapping, declarative transaction management, and more developer-friendly abstractions. Despite the emergence of these frameworks, JDBC remains essential knowledge for Java developers and continues to be used directly in performance-critical scenarios, legacy systems, and situations requiring fine-grained control over database interactions.

**Tags:** Databases, Connectors

**Properties:** 

**Wikipedia:** https://en.wikipedia.org/wiki/Java_Database_Connectivity
