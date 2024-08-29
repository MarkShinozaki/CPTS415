# Project - Airline Search Engine 

### Course Project Details

- The course project involves applying Big Data techniques and tools to a real-world problem. Students can choose from several suggested projects or propose their own, provided they align with the course's objectives and are approved by the instructor. Each project requires students to work with large datasets, implement efficient data processing algorithms, and deliver meaningful insights or applications based on the data.

- For example, one suggested project, Airline Search Engine, involves developing a tool that helps users search for flight information based on specific criteria, such as finding airports in a particular country, identifying airlines with certain characteristics, or recommending trips based on user preferences. The project would require students to work with large datasets and implement search and aggregation functionalities using MapReduce, SQL, or graph algorithms.

---

### What my Group did 

- Our group, named "Tres Amigos," worked on developing an Airline Data Search Engine. The primary goals of the project were to:

#### 1. Develop an End-to-End Application: You built a comprehensive and user-friendly airline data search engine that efficiently retrieves and displays information from large datasets.

#### 2. Implement Efficient Algorithms: The project required implementing algorithms for data processing and retrieval. These included searching for specific airlines and airports, finding flights between locations, and planning multi-flight trips.

#### 3. Create a User-Friendly Interface: The team focused on ensuring the application allowed users to input complex queries easily and receive clear, organized results.

#### 4. Support Essential Functionalities: The application included functionalities like searching for airports and airlines, aggregating airline data, and providing trip recommendations.

---

### How our Group Achieved the Requirements

1. **Data Cleaning and Uploading**: The team started by processing and cleaning the datasets related to airlines, airports, countries, planes, and routes using a combination of Python and Pandas. This data was then uploaded to a MongoDB database for efficient querying and retrieval. The main_data.py script handled these operations.

2. **Backend Development**: The team implemented the core logic for data querying and manipulation. This included creating scripts to run various data processing algorithms and to interact with the database, ensuring that the application could handle large volumes of data efficiently. The backend also included functionality for word similarity and matching, as demonstrated in test.py.

3. **Frontend Development**: The user interface was developed using PyQt, which provided a graphical interface for users to interact with the search engine. The interface allowed users to search for airports, airlines, routes, and more, with results displayed in an organized manner. This was achieved through the PyQt_app.py script, which managed the main window, widgets, and user interactions.

4. **Algorithm Implementation**: The team integrated several algorithms to handle search queries, trip recommendations, and data aggregation efficiently. These algorithms ensured that the application could return results quickly, even when working with large datasets.

5. **Testing and Validation**: Throughout the development process, the team performed extensive testing to ensure the application met performance and accuracy requirements. The application was evaluated based on its response time, scalability, and the efficiency of the algorithms used.

