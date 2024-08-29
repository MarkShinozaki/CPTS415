# Lectures & Notes 

### [WEEK 1](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%201)

#### [Course Overview](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%201/L1-1%20-%20Course%20Overview.pdf)
- This lecture provides an introduction to the course, covering key concepts and scope related to Big Data. It includes definitions, challenges, and examples of Big Data applications, emphasizing the course's objective to understand core concepts and implement real-world solutions. The lecture also outlines the course format, grading, and the types of assignments and projects that students will undertake.

#### [Big Data Overview](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%201/L1-2%20-%20Big%20Data%20Overview.pdf)
- This lecture focuses on the fundamental aspects of Big Data, including the "5 Vs" (Volume, Velocity, Variety, Veracity, and Value). It discusses the scale, speed, and complexity of Big Data, as well as the challenges associated with managing and extracting value from it. The lecture also touches on the different types of data sources and the importance of data quality, offering a comprehensive overview of what constitutes Big Data and why it is significant in today's digital world.

---

### [WEEK 2](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%202) 

#### [Relational DBMS](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%202/L2-1_Relational%20DBMS.pdf)

- This lecture introduces the basics of a Relational Database Management System (RDBMS). It covers key concepts like databases, the significance of using a DBMS, popular relational DBMS systems, and the foundational topics such as relational data models, query processing, and optimization. The lecture emphasizes the importance of relational databases in efficiently managing and querying large volumes of data.


#### [Relational Data Model](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%202/L2-2_Relational%20Data%20Model.pdf)

- This lecture dives into the Relational Data Model, explaining its concepts, constraints, and schema design. It discusses different data models, including the relational model and its structure based on sets. Key concepts such as tuples, attributes, and the state of a relation are covered, along with the significance of integrity constraints like key constraints, entity integrity, and referential integrity within relational databases.


#### [Design of Relational Data Models](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%202/L2-3_Design%20of%20Rellational%20Data%20Models.pdf)

- The focus of this lecture is on the design of relational data models, particularly normalization. It explores functional dependencies, normal forms (1NF, 2NF, 3NF, BCNF), and the need for normalization to avoid data redundancy and update anomalies. The lecture provides detailed steps for converting data models to higher normal forms to ensure the integrity and efficiency of the database design.

---

### [WEEK 3](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%203) 


#### [SQL](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%203/L3-1_SQL.pdf)

- This lecture covers the fundamentals of Structured Query Language (SQL), focusing on the syntax and use cases of various SQL commands. It includes examples of creating, updating, and managing databases and tables, as well as executing basic queries and data manipulation statements in SQL.

#### [Relational Algebra](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%203/L3-2_Relational_Algebra.pdf)

- This lecture introduces relational algebra as a formal system for querying relational databases. It discusses basic operations like selection, projection, union, intersection, and join, as well as more advanced concepts like division and set operations, which form the basis for relational query languages such as SQL.

---


### [WEEK 4](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%204)

#### [XML](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%204/L4-1_XML.pdf)

- This lecture introduces XML (eXtensible Markup Language) as a tool for managing semi-structured data. It covers the basics of XML, including its features, structure, and how it differs from HTML. The lecture also explores XML's applications in data exchange on the web, its role in data integration, and how it can represent relational databases.

#### [JSON](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%204/L4-2_JSON.pdf)

- This lecture provides an overview of JSON (JavaScript Object Notation), a lightweight data-interchange format. It explains the structure and syntax of JSON, how it is used for data exchange in web applications, and compares it to XML. The lecture also discusses the JSON data model, including flat vs. nested structures, and introduces JSON Schema for validating JSON data.


---

### [WEEK 5](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%205)

#### [Graph and RDF](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%205/L5-1%20-%20Graph%20and%20RDF.pdf)

- This lecture introduces the concept of graphs, focusing on their use in data representation, particularly in RDF (Resource Description Framework). The lecture covers various types of graphs, including directed, undirected, weighted, and unweighted graphs, and discusses how RDF uses a graph-based model to represent metadata on the web. It explains key concepts such as URIs, triples, and RDF schema, highlighting how RDF facilitates semantic interoperability and incremental knowledge building.


#### [Labeled Property Graph](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%205/L5-2-Labeled%20Property%20Graph.pdf)

- This lecture discusses the Labeled Property Graph model, which is commonly used in graph databases. It explains how vertices and edges are labeled and associated with properties, forming a flexible structure for representing complex data relationships. The lecture also covers various data storage schemes for graphs, introduces several graph databases like Neo4j, and explains how to use Cypher, a query language specifically designed for graph databases.


---


### [WEEK 6](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%206)

#### [Distributed Query Processing](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%206/L6-1%20Distributed%20Query%20Processing.pdf)

- This lecture introduces the concept of distributed query processing, which is essential for handling large datasets across multiple servers. The focus is on how to make Big Data manageable by breaking down queries and distributing the processing tasks. Key topics include parallel DBMS architectures, performance considerations like speedup and scaleup, and different parallelism strategies (intra-query, inter-query, intra-operation, and inter-operation). The lecture also discusses various partitioning strategies to optimize query processing.

#### [NoSQL 1](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%206/L6-2%20NoSQL%20I.pdf)

- This lecture covers the basics of NoSQL databases, focusing on the need for NoSQL solutions in handling Big Data, especially when traditional relational databases struggle. The lecture discusses the different types of NoSQL databases, their key features, and their advantages, such as flexibility, scalability, and performance in handling large-scale data operations.

#### [NoSQL 2](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%206/L6-3%20NoSQL%20II.pdf)

- Building on the first NoSQL lecture, this session delves deeper into specific types of NoSQL databases like column stores and document databases. It compares row stores and column stores, highlighting the advantages of column stores for certain types of queries. The lecture also covers MongoDB, a popular document database, and discusses its features, indexing mechanisms, and advantages in handling hierarchical data structures.


---

### [WEEK 7](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%207)

#### [Query Language](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%207/L7-1%20-%20Query%20Language.pdf)

- This lecture discusses the basic steps in query processing, including parsing, optimization, and evaluation. It introduces how relational algebra is used in relational database management systems (RDBMS) for query translation and optimization


#### [Query Language - Join Operations](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%207/L7-2%20-%20Query%20Optimization%20-%20Join%20Operations.pdf)

- This lecture covers various algorithms used to implement join operations in query processing. It discusses nested-loop join, block nested-loop join, merge-join, and hash-join, emphasizing the cost estimation and optimization strategies for each method.


---

### [WEEK 8](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%208)

#### [Graph Query Processing](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%208/L7-1%20Graph%20Query%20Processing.pdf)

- This lecture introduces the basics of graph query processing, discussing the challenges and complexities associated with querying graph-structured data. It covers various graph query types, such as path queries and graph pattern matching, along with algorithms like BFS for processing these queries.


#### [Approximate Graph Query Processing](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%208/L7-2%20Approximate%20Graph%20Query%20Processing.pdf)

- This lecture focuses on techniques for processing graph queries approximately rather than exactly. It covers methods like graph simulation and subgraph isomorphism, explaining how these can be used to quickly approximate answers to complex graph queries, which is useful in large-scale graph databases where exact answers may be computationally expensive.


#### [Approximate Relational Query Processing](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%208/L7-3%20Approximate%20Relational%20Query%20Processing%20.pdf)

- This lecture explores techniques for approximate query processing in relational databases. It discusses strategies like data synopses, histograms, and sampling to provide fast, approximate answers to queries. These methods are particularly useful when dealing with large datasets where exact query processing would be too slow or resource-intensive.

---

### [WEEK 9](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%209)

#### [Map Reduce 1](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%209/L9-1%20MapReduce%20I.pdf)

- Introduction to the MapReduce programming model, which is essential for processing large datasets. The lecture covers the basic concepts of MapReduce, including the mapping and reducing phases, data partitioning, fault tolerance, and parallelism. Examples like word count are used to illustrate these concepts.

#### [Map Reduce 2](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%209/L9-2%20MapReduce%20II.pdf)

- This lecture extends the MapReduce model to more complex scenarios, such as graph queries and Dijkstra's algorithm for finding the shortest paths in graphs. It also discusses the PageRank algorithm and its implementation using MapReduce, emphasizing the iterative nature and the challenges of applying MapReduce to these problems.


---

### [WEEK 10](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%2010)

#### [Hadoop - HDFS and MapReduce](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%2010/L10-1%20Hadoop%20-%20HDFS%20and%20MapReduce.pdf)

- This lecture introduces the Hadoop framework, focusing on the Hadoop Distributed File System (HDFS) and the MapReduce programming model. It covers how HDFS handles large-scale data storage with fault tolerance through replication and how MapReduce facilitates distributed data processing across many nodes. The lecture also discusses the architecture, design principles, and key functionalities of Hadoop.

#### [Hadoop Ecosystem](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%2010/L10-2%20Hadoop%20Ecosystem.pdf)

- This lecture expands on the broader Hadoop ecosystem, discussing various tools and components that work alongside Hadoop, such as Hive, Pig, HBase, and ZooKeeper. It explains how these tools enhance Hadoop's capabilities in data storage, processing, and management, making it a versatile platform for Big Data analytics. The lecture highlights the integration and use cases of each component within the ecosystem.

---

### [WEEK 11](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%2011)

#### [Apache Spark](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%2011/L11-1%20Apache%20Spark.pdf)

- This lecture introduces Apache Spark, a unified analytics engine for large-scale data processing. It covers the Spark ecosystem, including Spark Core, Spark SQL, Spark Streaming, MLlib, and GraphX. The lecture also explains the architecture of Spark, highlighting how it handles distributed data processing with its Resilient Distributed Dataset (RDD) and DataFrame APIs.

#### [Apache Spark - PySpark](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%2011/L11-2%20Apache%20Spark%20-%20PySpark.pdf)

- This lecture focuses on PySpark, the Python API for Apache Spark. It covers how to use PySpark for distributed data processing, including working with DataFrames, executing SQL queries, and integrating with various data sources like CSV, JSON, and JDBC. The lecture also introduces PySpark’s machine learning library (MLlib) and provides examples of creating and manipulating data in a Spark environment using Python.

---

### [WEEK 12](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%2012)

#### [NewSQL](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%2012/L12-1%20NewSQL.pdf)

- This lecture introduces NewSQL, a class of modern relational database management systems designed to provide the scalability of NoSQL systems while maintaining the ACID guarantees of traditional SQL databases. It covers the evolution from traditional OLTP systems to NewSQL, the key design principles of NewSQL systems, and examples of popular NewSQL databases like VoltDB and NuoDB.


#### [In-Memory DBMS](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%2012/L12-2%20In-Memory%20DBMS.pdf)

- This lecture focuses on In-Memory Database Management Systems (DBMS), which store the entire database in the main memory rather than on disk. It discusses the advantages of in-memory databases, such as reduced I/O overhead and faster query processing, and compares them to traditional disk-based databases. The lecture also explores the challenges and new bottlenecks introduced by in-memory systems, particularly regarding memory access and management.

---

### [WEEK 13](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Lectures-Notes/Week%2013)

#### [Data Quality 1](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%2013/L13-1%20Data%20Quality%20I.pdf)

- This lecture focuses on the importance of data quality in Big Data, highlighting the challenges posed by "dirty" data, which can lead to incorrect query results and significant financial costs. It covers various real-world examples of data quality issues and introduces the need for automated data cleaning tools and processes to maintain data integrity.

#### [Data Quality 2](https://github.com/MarkShinozaki/CPTS415-BigData/blob/Lectures-Notes/Week%2013/L13-2%20Data%20Quality%20II.pdf)

- This lecture continues the discussion on data quality by exploring methods for detecting and resolving inconsistencies in data. It introduces advanced concepts such as Conditional Functional Dependencies (CFDs) and Conditional Inclusion Dependencies (CINDs) as tools for improving data quality by enforcing integrity constraints and ensuring consistent data across different datasets.



