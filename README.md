# Assignments 

## [Assignment 1 - Relational Modeling](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Assignments/Assignment%201)

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

## [Assignment 2 - Data Formats](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Assignments/Assignment%202)

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

## [Assignment 3 - Parallel Processing ](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Assignments/Assignment%203)

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

## [Assignment 4 - Graph & Approximate Queries](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Assignments/Assignment%204)

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

## [Assignment 5 - Distributed Processing](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Assignments/Assignment%205)

1. **Hadoop**
    - **Task**: Write a program using Hadoop to compute and output daily average measurements for temperature and dew point temperature. The data is provided in a CSV file containing hourly recordings from Asheville Regional Airport, NC. Students are required to process this data using Hadoop, which involves writing a MapReduce program to aggregate the hourly data into daily averages.
      
    - **Big Data Concept**: This task focuses on the use of Hadoop, a key tool in Big Data processing, to handle large-scale data processing tasks efficiently through distributed computing.

2. **Spark RDDs**
    - **Task**: Write a program using Spark RDDs (Resilient Distributed Datasets) to compute and output the same daily average measurements. This involves using Spark's distributed data processing capabilities to achieve similar results as the Hadoop task, but with a focus on the RDD API.
      
    - **Big Data Concept**: The use of Spark RDDs demonstrates an alternative, more flexible approach to distributed data processing compared to Hadoop, highlighting Spark's efficiency and ease of use in Big Data scenarios.

3. **PySpark DataFrames**
    - **Task**: Implement the same daily average computation using PySpark and its DataFrame API. This part of the assignment emphasizes the use of DataFrames, which provide a higher-level abstraction for distributed data processing.
   
    - **Big Data Concept**: This task introduces PySpark DataFrames, which simplify the process of handling structured data and performing complex operations with less code and better performance optimization compared to RDDs.

#### Big Data Concepts Covered: 
- Distributed data processing using Hadoop MapReduce.
- The flexibility and efficiency of Spark RDDs in handling large datasets.
- High-level data processing with PySpark DataFrames for structured data.

  
--- 

## [Assignment 6 - Consistency & NewSQL](https://github.com/MarkShinozaki/CPTS415-BigData/tree/Assignments/Assignment%206)

1. **NewSQL Systems**
    - **Task**:Describe the main features of NewSQL systems, which are designed to combine the benefits of traditional relational databases (ACID compliance) with the scalability of NoSQL systems. The assignment asks students to provide real-world examples where NewSQL might outperform NoSQL, particularly in scenarios requiring complex transactions and high scalability.
      
    - **Big Data Concept**: NewSQL represents a modern approach to database management, offering both the consistency and transactional guarantees of traditional databases and the horizontal scalability typical of NoSQL systems.


2. **Data Consistency**
   
    - **Task**: Discuss various types of data consistency, including semantic, syntactic, and coverage consistency. Students are also introduced to the entity resolution problem, which involves identifying and linking different representations of the same real-world entity in a dataset.

    - **Big Data Concept**: Data consistency is crucial in maintaining the accuracy and reliability of large datasets, which is a significant challenge in Big Data environments.

3. **Functional Dependencies and Integrity Constraints**
   
    - **Task**: Analyze functional dependencies and inclusion dependencies within a relational dataset. The assignment also covers the challenges of maintaining data integrity when fixing one constraint might introduce violations in another, emphasizing the importance of consistent data management.

    - **Big Data Concept**: This task delves into the complexities of maintaining data integrity in Big Data systems, where ensuring consistent data across large, distributed datasets is critical for reliable operations.

#### Big Data Concepts Covered: 
- The integration of traditional database features with scalable architectures in NewSQL systems.
- Ensuring data consistency and accuracy in large, distributed datasets.
- Managing functional dependencies and maintaining data integrity in complex data environments.















