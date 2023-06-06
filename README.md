# IneuronFinalAssignment
This GitHub repository contains a collection of Spring projects developed by me as part of my training with iNeuron. These projects demonstrate various aspects of Java programming, JDBC, Servlets, Hibernate, and Spring Boot. Each project focuses on a specific functionality or concept, allowing users to gain hands-on experience with different technologies and frameworks.

1.	Polymorphic Shape Calculation: This Java program demonstrates polymorphism by defining an interface called Shape. The Shape interface includes methods to calculate the area and perimeter of a shape. The program also creates classes that implement the Shape interface for different types of shapes, such as circles and triangles. By utilizing polymorphism, the program can invoke the appropriate methods based on the shape type, enabling easy calculation of area and perimeter for different shapes.

2.	Invoking Parent Class Constructor from Child Class: This Java program showcases how to invoke the parent class constructor from a child class. It creates a child class object, which triggers the invocation of the parent class constructor. The program emphasizes key points about constructors, including their role in initializing objects, their relationship with inheritance, and how child class constructors automatically invoke the parent class constructor using the "super" keyword.

3.	Exception Handling with User Input Validation: This Java program takes an integer input from the user and throws an exception if the input is negative. It demonstrates exception handling by utilizing try-catch blocks. If the user enters a negative integer, an exception is thrown and caught, displaying an error message. The program highlights the importance of validating user input and handling potential exceptions gracefully.

4.	Bank Account Simulation: This Java program simulates a bank account, allowing users to deposit and withdraw money and check their balance. It demonstrates basic account management functionalities, such as updating the account balance based on deposits and withdrawals, as well as providing users with the ability to view their current balance.

5.	Abstract Class vs. Interface: This program showcases the difference between an abstract class and an interface in Java. It includes separate programs for both abstract classes and interfaces, highlighting their distinct features and use cases. Key points about abstract classes and interfaces are explained, including their purpose, when to use each one, and how they differ in terms of implementation and inheritance.

6.	Stream API Operations on Large Data Set: This Java program utilizes the Stream API to perform operations on a large data set. It demonstrates how to leverage the Stream API's functional programming features, such as filtering and sorting, to manipulate and process large amounts of data efficiently. The program showcases the ease and conciseness of using the Stream API for data processing tasks.

7.	Binary Search Algorithm Implementation: This Java program implements a binary search algorithm. It accepts user input for the target value and searches for it in a sorted array. If the target value is found, the program returns its index; otherwise, it displays a message indicating that the value was not found. The program showcases the efficiency and effectiveness of the binary search algorithm for searching in sorted collections.

8.	Printing Even and Odd Numbers using Threads: This Java program creates two threads. The first thread prints even numbers between 1 and 10, while the second thread prints odd numbers between 1 and 10. By utilizing multithreading, the program demonstrates concurrent execution of tasks and showcases how multiple threads can work independently to perform different operations simultaneously.

9.	Producer-Consumer Model using Multithreading: This Java program implements a producer-consumer model using multithreading. It consists of a producer thread that generates random numbers and adds them to a queue, and a consumer thread that reads numbers from the queue and calculates their sum. The program employs synchronization to ensure that the queue is accessed by only one thread at a time, preventing data inconsistencies and thread interference.

10.	Finding Second Largest and Second Smallest Elements in a List: This Java program reads a set of integers from the user and stores them in a List. It then finds the second largest and second smallest elements in the List. The program demonstrates list manipulation and finding extreme values within a collection, showcasing how to traverse and compare elements to determine the desired results.
	
11.	Connecting to MySQL Database using JDBC: This Java program connects to a MySQL database using JDBC (Java Database Connectivity). It reads data from a table and displays the results in the console. The program demonstrates how to establish a database connection, execute SQL queries, and retrieve and process the returned data.

12.	JDBC CRUD Application:
A Java program that utilizes JDBC to implement a simple CRUD (create, read, update, delete) application. It provides functionality for users to add, view, update, and delete records in a MySQL database table.

13. PostgreSQL Batch Update:
A Java program that establishes a connection to a PostgreSQL database and performs batch updates. It reads input data from a file and uses JDBC batch updates to efficiently insert the data into the database.

14. User Welcome Servlet:
A Java servlet that interacts with users through a web form. It reads the user's name using the GET method and displays a welcome message on the web page.

15. Data Display Servlet:
A Java servlet that retrieves data from a MySQL database table using JDBC and displays it in an HTML table on a web page. Users can view the data in a structured format.

16. Session Management Servlet:
A Java servlet that utilizes session management to maintain user state across multiple requests. It stores the user's name in a session object, allowing it to be accessed and displayed on multiple pages of the web application.

17. Blog Management Web Application:
A web application that follows the MVC pattern and enables users to create and view blog posts. The application uses servlets as controllers, JSPs as views, and a database as the model. Users can create new blog posts by filling out a form with a title, description, and content. The servlet handles storing the blog post data in the database and retrieving it to display it in a formatted way.

18. Hibernate Data Retrieval:
A Java program that utilizes Hibernate to connect to a MySQL database and retrieve data from a table. It uses Hibernate's object-relational mapping capabilities to map the table to a Java object and then displays the retrieved data on the console.

19. Hibernate Data Insertion:
A Java program that utilizes Hibernate to insert data into a MySQL database table. It maps the table to a Java object using Hibernate and performs data insertion. After inserting the data, it retrieves it from the database and displays it on the console.

20. Hibernate Data Update:
A Java program that uses Hibernate to update data in a MySQL database table. It maps the table to a Java object using Hibernate, performs the data update, and then retrieves and displays the updated data on the console.

21. Spring Boot Data Insertion:
A Spring Boot application that inserts data into a MySQL database table using JPA (Java Persistence API) and Hibernate. It utilizes Spring Data JPA to map the table to a Java object and perform data insertion.

22. Spring Boot Application with Spring Data JPA:
This Spring Boot application utilizes Spring Data JPA to retrieve data from a database. The application consists of entities for users and orders, allowing users to query orders by user. You can implement various querying methods, such as finding orders by user ID, user name, or any other relevant criteria using Spring Data JPA's query methods.

23. Spring MVC User Registration and Login:
This Spring MVC application provides user registration and login functionality. It includes a registration form that accepts user details, such as username, password, email, etc., and a login form that authenticates users. The application uses Spring MVC's form handling capabilities, allowing users to register and log in to access protected resources or perform specific actions.

24. Spring Boot REST API with JSON Data Insertion:
This Spring Boot application implements a REST API that accepts JSON requests with data and inserts it into a MySQL database table. It utilizes Spring MVC for handling incoming requests, and Spring Data JPA along with Hibernate for mapping the table to a Java object and performing data insertion. You can define the appropriate endpoints and request mappings to handle JSON data and persist it in the database.

25. Spring Boot Application with Method Logging using Spring AOP:
This Spring Boot application demonstrates the usage of Spring AOP (Aspect-Oriented Programming) to log method calls. It includes a service class with various methods performing operations, and Spring AOP is configured to intercept these method calls and log the input and output parameters to the console. This enables easy tracking and monitoring of method invocations within the application.

26. Spring Boot REST API for Product Management:
This Spring Boot application exposes a REST API for managing a list of products. The API allows users to perform CRUD operations (create, read, update, delete) on products. Users can create new products, update existing ones, delete products, and retrieve a list of products. This application utilizes Spring MVC for handling HTTP requests and implementing the necessary endpoints for managing products.

27. Spring Boot Application with Service Registration using Spring Cloud and Eureka Server:
This Spring Boot application integrates with Spring Cloud and Eureka Server to register a service. It exposes a REST API for retrieving data from a database, and the API is automatically discovered by Eureka Server. This allows for a scalable microservices architecture, where services can register themselves and communicate with each other through Eureka Server.

28. Spring Boot Application with Externalized Configuration using Spring Cloud Config Server:
This Spring Boot application uses Spring Cloud Config Server to externalize configuration properties. It includes a property file that defines properties for database connection and other application settings. By connecting to the Config Server, the application retrieves the configuration properties at runtime, providing flexibility and ease of configuration management.

29. Spring Boot Application with Filtered, Sorted, and Paged REST API using Spring Data JPA:
This Spring Boot application utilizes Spring Data JPA to retrieve data from a database and expose it as a REST API. The API allows for filtering, sorting, and paging of the data. Users can apply filters based on specific criteria, sort the data based on different attributes, and paginate the results to retrieve data in smaller, manageable chunks. This application leverages Spring Data JPA's querying capabilities to achieve these functionalities.

30. Spring Boot Application with Circuit Breaker using Spring Cloud Circuit Breaker:
This Spring Boot application incorporates Spring Cloud Circuit Breaker to handle failures in a REST API. The API utilizes the circuit breaker pattern to handle timeouts and other errors. By configuring a circuit breaker, the application can prevent cascading failures and provide fallback mechanisms when services are unavailable or experiencing issues. Spring Cloud Circuit Breaker provides a resilient approach to handling failures in a distributed system.








