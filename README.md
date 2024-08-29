# Assignments 

## [Assignment 1](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Assignments/Assignment%201)

1. **Big Data Concepts**
    - Students are required to provide an example of a Big Data application and explain the "Five Vs" of Big Data: Volume, Velocity, Variety, Veracity, and Value. This part of the assignment introduces students to the foundational concepts of Big Data, demonstrating how these characteristics apply in real-world scenarios like social media analytics.

2. **Relational Data Model**
    - This section involves analyzing the OpenFlights Airports Database, which contains information on over 10,000 airports worldwide. Students must define terms related to the relational data model, such as relation schema, attribute, and relation instance, using the airport database as a reference. The assignment also requires students to identify primary keys, foreign keys, and functional dependencies in the dataset, reinforcing their understanding of relational database schemas and their relationships.
  
3. **Functional Dependencies**
    - Students are tasked with applying Armstrong’s axioms to derive new functional dependencies from those identified in the relational data model section. This exercise solidifies their understanding of the rules governing functional dependencies and how they apply to maintaining data integrity within a database.

4. **Relational Algebra**
    - The final part of the assignment asks students to express specific queries in relational algebra using a provided database schema. This includes tasks like identifying theaters showing specific movies, listing details of theaters featuring films by certain directors, and identifying pairs of actors in the same movie. This section helps students practice the application of relational algebra in querying databases.

#### Big Data Concepts Covered: 
- Introduction to the "Five Vs" of Big Data.
- Understanding and working with relational data models.
- Exploring functional dependencies and their importance in data integrity.
- Application of relational algebra for querying relational databases.

---

## [Assignment 2](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Assignments/Assignment%202)

1. **XML**
    - Students are required to create XML documents to represent the data for a construction project management company. This includes defining XML schemas and Document Type Definitions (DTD) for the XML documents. The assignment emphasizes the importance of structuring and validating data in XML format, which is crucial for data interchange in Big Data applications.

2. **JSON**
    - This section involves modeling the same construction project management data in JSON format and creating JSON Schemas for validation. Students learn how to represent hierarchical data structures in JSON, which is widely used in modern web applications and APIs.

3. **Property Graph**
    - The assignment concludes with creating a Labeled Property Graph using a graph database management system like Neo4j. Students must define vertices, edges, and properties for the project management data, allowing them to explore the benefits of graph databases for managing complex relationships within datasets.

#### Big Data Concepts Covered: 
- Structuring and validating data using XML and JSON formats.
- Understanding the use of graph databases for managing and querying data with complex relationships.
- Emphasizing the flexibility and scalability of NoSQL data models in handling diverse data types.

---

## [Assignment 3](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Assignments/Assignment%203)

1. **Parallel Data Models**
    - This section covers the principles of parallel computing, specifically focusing on the speed-up of tasks when executed on multiple processors. Students are asked to calculate speed-up and optimal speed-up using Amdahl’s Law, and to compare different parallel system architectures (Shared Memory, Message Passing, Data Parallel). This section introduces students to the challenges and benefits of parallel data processing, which is a key concept in Big Data environments where tasks must be distributed across multiple processors.
  
2. **ACID vs BASE**
    - This section explores data consistency models, focusing on the differences between ACID (Atomicity, Consistency, Isolation, Durability) and BASE (Basically Available, Soft state, Eventually consistent). Students also learn about CAP Theorem, which discusses the trade-offs between Consistency, Availability, and Partition Tolerance in distributed systems. Understanding these models is essential in Big Data systems where consistency requirements vary depending on the application.

3. **Quorum Consensus**
    - The concept of Quorum Consensus is introduced as a method to ensure data consistency in distributed systems. This method is crucial in Big Data scenarios where data replication and consistency across nodes are necessary to prevent conflicts and ensure system reliability.

4. **Relational DB**
    - Students are asked to describe and compute the cost of a block nested join algorithm in relational databases, emphasizing the importance of query processing efficiency in managing large datasets. This section is critical for understanding how relational databases handle queries in Big Data environments.

#### Big Data Concepts Covered: 
- Parallel data processing and Amdahl’s Law.
- ACID and BASE consistency models in distributed systems.
- CAP Theorem and its implications for Big Data.
- Quorum Consensus for data consistency.
- Efficient query processing in relational databases.


---

## [Assignment 4](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Assignments/Assignment%204)

1. **Graph Query Processing**
    - This section tests the understanding of basic graph algorithms, focusing on label-constrained reachability queries and reliability in network graphs. Students write algorithms to solve these problems, which are fundamental in processing and querying large-scale graph data, a common Big Data challenge.

2. **Approximate Query Processing**
    - Students work with Haar wavelet decomposition for data approximation, which is a technique used in Big Data to reduce the size of datasets while preserving essential information for query processing. This section highlights the importance of efficient data synopsis and approximation techniques in handling and querying large datasets.
  
3. **MapReduce**
    - The assignment involves writing MapReduce programs to solve common Big Data problems, such as finding common friends on social networks and identifying the top 10 most frequent keywords in web pages. This section reinforces the use of MapReduce as a powerful tool for distributed data processing, which is central to Big Data analytics.
   
4. **Graph Parallel Models**
    - This section extends the use of MapReduce to solve graph-related problems, such as finding 2-hop common contacts and d-bounded reachability queries. These tasks require an understanding of how to parallelize graph algorithms, which is crucial in processing large graph datasets in a distributed environment.

#### Big Data Concepts Covered: 
- Graph query processing and algorithm development.
- Data approximation and synopsis using Haar decomposition.
- MapReduce for distributed data processing.
- Parallel processing of graph data using MapReduce.


---

